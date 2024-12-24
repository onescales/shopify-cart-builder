# shopify-cart-builder
Simple form to Let you build a cart for you customer to provide them a special url or qr code for a Shopify store.

This tutorial code requires a little bit of copy and paste in your Shopify backend to make it work but should take about 5 minutes no more.

For a visual overview and full details, see our article at https://onescales.com/blogs/main/shopify-pre-loaded-cart and our youtube video at https://www.youtube.com/watch?v=3X33Iwu4PjE

# Steps

1. Login to Shopify Backend
2. Customize your theme and add a new "page template" called "Cart Builder" based on "Default Page".
3. In this "Cart Builder" page template add a new section called "Custom Liquid" and copy the code from https://github.com/onescales/shopify-cart-builder/blob/main/shopify-cart-builder.liquid and save.
4. Create New Page (for example - Shopify Cart Builder) and Select "theme template" "Cart Builder"
5. Visit "Cart Builder" page and use the form to get a url of your cart
- Checkbox any products you want to add to cart and specify the quantity. Note you will need to select at least 1 product for the url builder to work.
- Select "Send visitor to" either cart or checkout page
- Specify "Discount Code" if you want to add a coupon code. Discount code is optional.
- Click on "Build URL".
- Grab either the QR code or the url via copy and provide to your customers. Note you can right click and "save as image" the qr code to use later.
6. Start Using It. Enjoy!

# Additional Notes
- Currently limited to 1000 products. If you have more than 1000 products in your catalog, you will need to customize code on your end.
- If customer had an existing cart already, this url will replace it.
- Note that the above instructions are to create a new page and add liquid code. These instructions will create a public live page which most of you probably don't want to showcase to the world so you will have to add a password to it or use the liquid in this repo to do it in your own protected way. You can also make visibility "hidden" and use it as a logged in admin by clicking on view page button.
- QR Code generated is using quickchart.io
- If you add a Discount code that is wrong, the url will fail when you try it.
- This form is an easy tool to use based on Shopify's Cart Permalink - https://help.shopify.com/en/manual/products/details/cart-permalink
- All code and instructions are as is. By reading this repository, readme or any code, you acknowledge that you are solely responsible for your own doings.

Hope you liked this!

# Support Us / Donate
If this helped you in any way, please consider supporting us at https://onescales.com/pages/support-us

# Suggestions, Comments and Contact
If you have any suggestions, comments, insight or just want to say hi, thanks or share your experience, you can contact us at:
- Our WebSite: https://onescales.com/
- Contact Us: https://onescales.com/pages/contact
- Youtube Channel: https://www.youtube.com/@onescales
- Twitter/X: https://twitter.com/one_scales
- LinkedIn: https://www.linkedin.com/company/one-scales/





