==================================
 Auto invoice creation on payment
==================================

Installation
============

* `Install <https://odoo-development.readthedocs.io/en/latest/odoo/usage/install-module.html>`__ this module in a usual way

Configuration
=============

* Set acquirers:
    * Using user with ``Financial Manager`` access go to ``Accounting / Configuration / Journals / Journals``
    * Set ``Payment acquirer`` for every journal to be used for eCommerce payments registration.


Usage
=====

When payment is processed thru some provider (acquirer), such as PayPal,
the invoice (Account voucher) is created with corresponding accounting entries.
You can look up created vouchers in ``Accounting / Journal Entries / Journal Vouchers``
(using user with ``Technical Features`` enabled and with Accountant rights) to see those payments.
