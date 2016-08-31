==================================
 Auto invoice creation on payment
==================================

Installation
============

* `Install <https://odoo-development.readthedocs.io/en/latest/odoo/usage/install-module.html>`__ this module in a usual way

Configuration
=============


* `Enable technical features <https://odoo-development.readthedocs.io/en/latest/odoo/usage/technical-features.html>`__
* Set acquirer for every journal to be used for eCommerce payments registration.

Usage
=====

When payment is processed thru some provider (acquirer), such as PayPal,
the invoice (Account voucher) is created with corresponding accounting entries.
You can look up created vouchers to see that payments.
