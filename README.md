# Aliexpress default wishlist visualiser
Visualise Aliexpress default wishlist from allItems React state

## Instructions

You need to have the [React DevTools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) installed in Chrome to get the items in the wishlist.

### Steps:
1. Open the [Aliexpress wishlist page](https://www.aliexpress.com/p/wishlist/index.html)
1. Scroll the page down in order to fetch more items
1. Open JavaScript Console (⌘+⌥+J on MacOS, ctrl+alt+J on Windows & Linux)
1. Open the Components tab (might be hidden under the ">>" item in the tabs at the top
1. Click the Context.Provider in the components tree (see image below)
1. Expand the "value" property under props by clicking the caret in front of it
1. Right click the "allItemsList" property and select "Copy value to clipboard"
1. <a href="https://gadgetmies.github.io/aliexpress_default_wishlist/public/" target="_blank">Open the visualiser page</a>
1. Paste the value from the clipboard to the text area
1. Click process

<img width="639" alt="image" src="https://github.com/gadgetmies/aliexpress_default_wishlist/assets/71213783/6efdabd3-9a32-474b-9664-6980cdc31e31">

