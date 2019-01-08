## This is no longer actively maintained.

Shopify Naked theme
---------------------------------------------

This is a completely naked Shopify theme. It's based on <a href="https://github.com/Shopify/skeleton-theme">Shopify Skeleton</a> and will track the changes applied to that in terms of liquid code. I found myself stripping out so much HTML and CSS I didn't need for client sites this would save me time creating new themes. This is meant for advanced Shopify theme developers, I have left in some semantic HTML such as some header tags and list items but that's about it. I've also left in the product variant JS for now.

You can view it here if you really want to see a blank site <a href="https://shopify-naked.myshopify.com/">https://shopify-naked.myshopify.com/</a>.

Download / Setup
---------------------
1. <a href="https://github.com/thisiscapra/shopify-naked/archive/master.zip">Download</a> the latest version
2. or clone the git repo: <code>git clone git@github.com:thisiscapra/shopify-naked.git</code>
3. I like to use the Shopify theme gem for development <a href="https://github.com/Shopify/shopify_theme">shopify_theme</a>
4. Import some dummy product data to start developing <a href="http://www.tetchi.ca/wp-content/uploads/2013/04/products1.csv">download CSV file</a>

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── config
│   └── custom Theme Settings
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── optional custom code snippets
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── index.liquid
│   ├── page.liquid
│   ├── product.liquid
│   └── search.liquid
```
