---
title: Add products to a shared catalog
description: Learn about adding products to a shared catalog, either individually or in groups by category.
exl-id: c88b46b4-cea8-4f65-b7e4-6681bab64d41
---
# Add products to a shared catalog

Products can be added to a shared catalog either individually or in groups of multiple products by category.

The following requirements must be met for a complex product (such as bundle, grouped, or configurable) to be visible from the storefront in a shared catalog:

- All [associated products](../catalog/product-configurations.md) and options must be assigned to the same shared catalog and enabled in the primary catalog.
- For [configurable](../catalog/product-create-configurable.md) and [grouped](../catalog/product-create-grouped.md) products, only the enabled associated products are visible.
- For a [bundle](../catalog/product-create-bundle.md) product, all options must be included in the shared catalog.

   ![Select Products for Catalog](./assets/shared-catalog-select-products-step-1.png){width="600" zoomable="yes"}

## Method 1: Add a single product

1. On the _Admin_ sidebar, go to **[!UICONTROL Catalog]** > **[!UICONTROL Products]**.

1. For the product in the grid that you want to add, go to the _[!UICONTROL Action]_ column and click **[!UICONTROL Edit]**.

1. Scroll down, expand ![Expansion selector](../assets/icon-display-expand.png) the _[!UICONTROL Product in Shared Catalogs]_ section, and do the following:

   - Select the checkbox of each shared catalog where the product should appear. To choose all catalogs, click **[!UICONTROL Select all]**.

      ![Product in Shared Catalogs](./assets/shared-catalog-assign-from-product.png){width="600" zoomable="yes"}

      The name of each selected catalog appears in the _[!UICONTROL Shared Catalogs]_ field.

      ![Shared catalogs assigned](./assets/shared-catalog-assigned.png){width="600" zoomable="yes"}

   - Click **[!UICONTROL Done]** to save the settings.

1. When complete, Click **[!UICONTROL Save]**.

## Method 2: Add multiple products

1. On the _Admin_ sidebar, go to **[!UICONTROL Catalog]** > **[!UICONTROL Shared Catalogs]**.

1. For the shared catalog in the grid, go to the _[!UICONTROL Action]_ column and select **[!UICONTROL Set Pricing and Structure]**.

1. In the category tree, do any of the following:

   - To include all products, click **[!UICONTROL Select all]** or select the checkbox of the parent category.
   - To include specific categories of products, select the checkbox of each category that you want to include.
   - To include or exclude an individual product, select or deselect the checkbox of product.

   The notation below each category in the tree shows the number of products from the category that are currently included in the shared catalog. The notation below the [root category](../catalog/category-root.md) shows the total number of products from all categories that are currently selected for the shared catalog.

1. To view category products in the grid, click the name of the category in the tree.

   When a category is selected, the following occurs:

   - The toggle in the first column of the grid is set to `On` for each selected product.
   - If a product is assigned to multiple categories and is omitted in one of them, it remains available through the other categories and through [catalog search](../catalog/search.md).
   - The system automatically sets [Category Permissions](../catalog/category-permissions.md) to `Allow` for the selected products.
