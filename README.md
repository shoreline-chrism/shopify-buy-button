# Shopify Buy button example site

Static website presenting products defined on Shopify. It uses Shopify's GraphQL API to get a list of products and generates website where you can buy products using Shopify.

## Deploy on Netlify

Deploy this on Netlify by configuring some variables found in your Shopify Private App

[![Launch on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/shoreline-chrism/shopify-buy-button)

## Development

Setup your python environment.

```sh
pipenv install
```

### Build

```sh
pipenv run python build.py
```

## License

Code is licensed under MIT license.
