# Vuetify Shopfiy E-Commerce Theme

Thank you for purchasing the theme

#### Features
* Plugin integrations
  * axios
  * shopify
  * vue-meta
  * vue-scrollactive
  * vuex-router-sync
  * webfontloader
* Over 20 custom components
* Data caching
* Ready to deploy on [zeit now](https://zeit.co)
* Dynamically generated content
  * Intelligently builds site based upon products/collections

## Getting Started
Must be pre-built to reflect changes in shopify store. Uses pre-rendering for SEO and pages are generated after build.

### Create a new shopify account
Navigate to [https://shopify.com](https://shopify.com) and register for a new account.

### Create a new private application
Create a new private application so that we can access the Shopify API.

![create-app-1](/assets/create-app-1.png?raw=true)

<br>

![create-app-2](/assets/create-app-2.png?raw=true)

<br>

![create-app-3](/assets/create-app-3.png?raw=true)

<br>

![create-app-4](/assets/create-app-4.png?raw=true)

### Get storefront api token and update .env
Locate your API key and update your .env file.

![storefront-access-token](/assets/storefront-access-token.png?raw=true)

<br>

![env-file](/assets/env-file.png?raw=true)

Explanation of variables:

```bash
SHOPIFY_DOMAIN # This is the domain given to you by Shopify during registration
SHOPIFY_ACCESS_TOKEN # This the token generated from your private application
SHOPIFY_GOOGLE_ANALYTICS # Google Analytics key
SHOPIFY_DEFAULT_COLLECTION # This defaults to frontpage as this is the default collection of Shopify
SHOPIFY_FEATURED_COLLECTION # This is the collection used for generating featured sliders
SHOPIFY_CAROUSEL_1_HANDLE # This is the first carousel item on the home page
SHOPIFY_CAROUSEL_2_HANDLE # This is the second carousel item on the home page
SHOPIFY_CAROUSEL_3_HANDLE # This is the third carousel item on the home page
SHOPIFY_TRENDING_1_HANDLE # This is the first trending item on the home page
SHOPIFY_TRENDING_2_HANDLE # This is the second trending item on the home page
```

### Create some collections

Create a new collection so that we can group our products into categories.

![create-collection-1](/assets/create-collection-1.png?raw=true)

<br>

![create-collection-2](/assets/create-collection-2.png?raw=true)

### Create some products

Create new products and assign them to existing categories. These categories are used for dynamically generating your site. Later we will take these collection names and add them to the .env file.

![create-product-1](/assets/create-product-1.png?raw=true)

<br>

![create-product-2](/assets/create-product-2.png?raw=true)

At this point, ensure that your packages are installed and run `yarn serve` or `npm run serve`.

If you get stuck or have any questions, please reach out to johnleider on our [community discord server](https://discord.gg/w2qKXtD).


