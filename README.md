# Purchase Order Portal Preview

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Community%2C_Enterprise-2563EB) ![License](https://img.shields.io/badge/License-OPL--1-0F766E)

Sale orders have a Preview button that opens the customer portal view. Purchase orders do not. This app adds the same button, so buyers see exactly what the vendor will see before sending.

## What it does

- Preview button on the purchase order form that opens the vendor portal page

## How to use it

1. Open a purchase order and click Preview.

## Technical notes

Technical name `purchase_order_preview`, Odoo 17.0.

Adds an `act_url` action on `purchase.order` built from `get_portal_url()`. Depends on `purchase` and `portal`.

## Get the module

This module is not on the Odoo App Store yet. Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=purchase_order_preview) for a licence, the full source code and installation on your database.

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=purchase_order_preview%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module source is private and comes with the licence.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).
