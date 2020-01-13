## Shopify theme based on Brooklyn theme by Shopify

This theme is based on the official free [brooklyn](https://themes.shopify.com/themes/brooklyn) theme for Shopify.

This version includes a few bugfixes and has some additional features.

The official theme was exported and ported to Slate 0.14.0, so now this theme is a Slate theme. You will need to install [Slate 0.14.0](https://shopify.github.io/slate/docs/0.14.0/) to work with and build this theme.


### Bugs fixed:

1. Cart drawer opening by itself after being closed. This happened if the cart was being loaded or updated and once the loading is completed, the drawer's open function is called, even if it's unintended. The drawer now opens only on adding an item is added to the cart.
2. On opening cart drawer, there was an empty space of about 18px between the slideshow and the drawer. It is now fixed by calling $(window).resize() whenever the drawer is opened or closed.

### Additions:

1. Trust badges including a generic Trustlock badge and PayPal, along with theme option to enable/disable it.
2. Theme option to limit number of rows shown in Featured Collection section along with a 'View all' button.
3. Search button on mobile navigation bar. Also added theme option to show or hide it.
4. Theme settings for shortcut icons of several sizes.
5. Theme option for stores offering free shipping on all products. This causes "Shipping calculated at checkout." text to be replaced with "Free Shipping".
6. Product reviews section and a theme option to enable/disable it.

### Other changes:

1. Make the Payful style the default.
2. Removed 'Powered by Shopify' text.
3. The default value for "Shipping" is now "Free" on the Checkout page.
4. Made code a little bit more efficient in featured_products.liquid


## License
Shopify License?
