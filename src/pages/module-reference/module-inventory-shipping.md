---
title: InventoryShipping
description: README.md contents of the module from the source code
---

# InventoryShipping module

The `InventoryShipping` module integrates MSI business logic into Magento's shipping logic.

This module is part of the new inventory infrastructure. The
[Inventory Management overview](https://developer.adobe.com/commerce/webapi/rest/inventory/)
describes the MSI (Multi-Source Inventory) project in more detail.

## Installation details

This module is installed as part of Magento Open Source. It cannot be deleted or disabled.

## Extension points and service contracts

All public interfaces related to this module are located in the `InventorySourceDeductionApi` and
`InventorySourceSelectionApi` modules.
Use the interfaces defined in those modules to extend this module.
