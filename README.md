# shopify-narrative-theme-updates
Customizations to Shopify's Narrative theme

Shopify's Narrative theme is really beautiful in many ways, except for the product page, which is a strange anomoly. The product page presents the gallery of product images below the product description. The images are absolutely huge, and there is no padding or visual separation between them. 

There are some things you can do to make this better.

  1. Stop the addtional images from being displayed at all, and just have the main product image displayed
     How to to this: https://github.com/melanie-p/shopify-narrative-theme-updates/blob/main/remove-images-on-product-page
     Caveats with this approach: the customer will have to know to click on the main product image to see the additional images, so they may never see some of the
     images you want them to see.
     
  2. Force each image to take up the same amount of space in the image gallery container, rather than scaling the images to fill the container 
     How to do this: https://github.com/melanie-p/shopify-narrative-theme-updates/blob/main/smaller-product-page-gallery-images
     Caveats with this approach: a) if you're using different image sizes, some of the image might get cut off in the gallery. It's best if you use square images 
     if you're going to make this change, b) I think the approach I used is a little bit of a hack -- it's kind of brute forcing things. But I've tested in on
     my shop and it works fine, so I'm okay with it.
