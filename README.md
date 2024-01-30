# Aliexpress default wish list visualiser
Visualise Aliexpress default wish list from allItems React state

## The issue

Aliexpress limits the amount of items you can store in your default wish list and once you reach that amount, you will be unable to add items to any wish list as the items are added to the default wish list first from where those can be moved to other lists. To add insult to injury, there is no page for viewing the default wish list, so it is very difficult to clean up the default list.

## The solution

Using the <a href="https://gadgetmies.github.io/aliexpress_default_wishlist/public/" target="_blank">Visualiser page</a> in this repository and the instructions below you will be able to get a list of the items in the default wish list and thus you know which items you should move in order to clean up the default wish list.

## Instructions

You need to have the [React DevTools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) installed in Chrome to get the items in the wish list.

### Steps:
1. Open the [Aliexpress wish list page](https://www.aliexpress.com/p/wishlist/index.html)
1. Scroll the page down in order to fetch more items (you can e.g. keep page down pressed until you reach the end of the list)
1. Open JavaScript Console (⌘+⌥+J on MacOS, CTRL+SHIFT+J on Windows & Linux)
1. Open the Components tab (might be hidden under the ">>" item in the tabs at the top
1. Click the Context.Provider in the components tree (see image below)
1. Expand the "value" property under props by clicking the caret in front of it
1. Right click the "allItemList" property and select "Copy value to clipboard"
1. <a href="https://gadgetmies.github.io/aliexpress_default_wishlist/public/" target="_blank">Open the visualiser page</a>
1. Paste the value from the clipboard to the text area
1. Click process

<img width="639" alt="image" src="https://github.com/gadgetmies/aliexpress_default_wishlist/assets/71213783/6efdabd3-9a32-474b-9664-6980cdc31e31">

