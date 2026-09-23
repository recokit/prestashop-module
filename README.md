# RecoKit for PrestaShop

Free PrestaShop module for displaying RecoKit product recommendations: similar products, complementary products, bundles, comparison, cart recommendations and add-to-cart suggestions.

The module connects the shop to the RecoKit SaaS API. Catalog analysis and recommendation processing run on RecoKit infrastructure; the module does not run an AI model on the merchant's server.

## Install

1. Download the ZIP from the [RecoKit PrestaShop page](https://recokit.fr/prestashop.html) (the public GitHub release can be used once this repository is published).
2. In PrestaShop, open **Modules and Services → Install a module**.
3. Upload the ZIP without extracting it, then open **Configure**.
4. The RecoKit account is created or associated automatically after a successful connection.

The initial synchronization is automatic. Product associations and AI recommendations are asynchronous: sales associations may take a few minutes, and AI enrichment can take longer for a large catalog.

## Requirements

- PrestaShop 8.x
- PHP 7.4 or newer
- HTTPS-enabled shop

## Privacy

The module sends the catalog data required to provide recommendations to the RecoKit API over HTTPS. Store data is isolated by shop. Sales events are used for that shop's co-purchase recommendations and are not used to train a global model. The merchant remains responsible for consent and privacy notices for analytics cookies.

## Support

See the [installation guide](https://recokit.fr/docs/prestashop-installation.md) or open an issue with the PrestaShop version and module logs. Never include API keys in an issue.
