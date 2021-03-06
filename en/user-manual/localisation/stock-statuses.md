Stock Statuses
==============

<div class="uk-alert-info uk-alert">
  <span class="uk-icon-info-circle"></span> You can switch between Basic and Advanced modes from the tabs below.
</div>
<ul class="uk-tab" data-uk-tab="{connect:'#doc-tabs', animation: 'fade'}">
    <li><a href="">Basic Mode</a></li>
    <li><a href="">Advanced Mode</a></li>
</ul>

In this section you may create **Out of Stock** statuses to be displayed on the product page when a product is out of stock. The stock status name is arbitrary.

The default stock status for **Out of Stock** products can be edited under the option tab in [Settings](docs/user-manual/system/settings/option). The specific **Out of Stock Status** for a product can be edited in the **Data** tab in [Products](docs/user-manual/catalog/products/data).

<ul id="doc-tabs" class="uk-switcher uk-margin">
    <li markdown="1">![stock statuses backend](_images/basic-stock-statuses.png)</li>
    <li markdown="1">![stock statuses backend](_images/stock-statuses.png)</li>
</ul>

##Styling on stock status

This feature comes with Arastta 1.2.0 version. It allows you to set different colors for each status.

<ul id="doc-tabs" class="uk-switcher uk-margin">
    <li markdown="1">![stock statuses backend edit](_images/basic-stock-statuses-1.png)</li>
    <li markdown="1">![stock statuses backend edit](_images/stock-statuses-1.png)</li>
</ul>

![stock statuses front-end](_images/stock-statuses-2.png)

##Allow Pre-Order

Since Arastta 1.5, it possible to allow customers order the products even if their stock status is "out". If you want to allow "pre-order" feature for specific stock statuses, then you can choose _Yes_ from **Pre-Order** option for that statuses. All products have that status can be ordered by the customers even if their stock value is 0 (zero).
