# RecoKit for PrestaShop

AI product recommendations for PrestaShop stores, with a free module and a cloud service that works from the first day of a new catalog.

[Download the latest module](https://github.com/recokit/prestashop-module/releases/latest) · [Installation guide](https://recokit.fr/docs/prestashop-installation.md) · [RecoKit website](https://recokit.fr/prestashop.html)

## What it adds to your store

- Similar products on product pages
- Complementary products and cross-sell suggestions
- Product bundles
- Product comparison
- Recommendations in the cart and add-to-cart modal
- Add-to-cart actions directly from recommendation cards

RecoKit combines catalog content, semantic analysis and store signals. The module itself stays lightweight: catalog analysis and recommendation processing run on RecoKit infrastructure, not on the merchant's server.

## Install in a few minutes

1. Download `recokit-prestashop-1.3.3.zip` from the [latest release](https://github.com/recokit/prestashop-module/releases/latest).
2. In PrestaShop, open **Modules and Services → Install a module**.
3. Upload the ZIP without extracting it, then open **Configure**.
4. The RecoKit account is created or associated automatically after a successful connection.

The initial synchronization is automatic. Sales associations may take a few minutes and AI recommendations can take longer for a large catalog. The manual synchronization button is intended for recovery after an interruption or catalog mismatch.

## Requirements

- PrestaShop 8.x
- PHP 7.4 or newer
- HTTPS-enabled shop

## Privacy and data isolation

The module sends the catalog data required to provide recommendations to the RecoKit API over HTTPS. Store data is isolated by shop. Sales lines are used for that shop's co-purchase recommendations and are not used to train a global model shared between merchants. Personal customer contact and payment details are not needed for recommendation processing.

The merchant remains responsible for consent and privacy notices for analytics cookies.

## Support

Read the [full installation guide](https://recokit.fr/docs/prestashop-installation.md), visit the [RecoKit PrestaShop page](https://recokit.fr/prestashop.html), or open an issue with the PrestaShop version and module logs. Never include API keys in an issue.

## License

The module is distributed free of charge. RecoKit cloud service plans and usage limits are described on [recokit.fr](https://recokit.fr/).
