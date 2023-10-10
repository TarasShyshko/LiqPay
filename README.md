INTRODUCTION
------------

This module provides a Drupal Commerce payment method to embed the payment
services provided by LiqPay.

It efficiently integrates payments from various sources such as:
- credit cards;
- cash via self-service terminals (offline payments);
- email receipts;
- privat24 banking or liqpay accounts.

This module use LiqPay API v3.0.

REQUIREMENTS
------------

- [Token](http://drupal.org/project/token)
- Commerce Payment (from [Commerce](http://drupal.org/project/commerce) core)
- Commerce Order (from [Commerce](http://drupal.org/project/commerce) core)

INSTALLATION
------------

1. Install the Commerce LiqPay module by copying the sources to a modules
   directory, such as `/modules/contrib` or `sites/[yoursite]/modules`.
2. In your Drupal site, enable the module.

CONFIGURATION
-------------

API keys can be configured at settings page:
Commerce -> Configuration -> Payment -> Payment gateways -> LiqPay -> edit ->
Actions table -> Enable payment method: LiqPay -> edit -> Payment settings.
