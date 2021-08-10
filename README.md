## Magento 2 Bundle Pack

Bundle Pack extension for Magento 2 allows users to setup and manage all bundle packs which helps customers buy more products in bundles.

### Description

**Magento 2 Bundle Pack Extension** allows you to display bundles match the main products and their discounts on product tab or below product info which your customers may interested. 

Moreover, this extension also makes your website more attractive and looks beautiful.

- Increase website performance, improve customer experience

- Increase sales performance

- Effective customer navigation tools

### Look in frontend

Bundle Pack extension for Magento 2 will help your website in increasing customer experience by showing attractive bundles and discounts. It will get your customer's attractive and increase the sale performance. 

![Magento 2 Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/product_tab.png)

And improve customer experience by using convenient popup to select optional products

![Magento 2 Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/popup.png)

### Highlight Features

- Add Packages with the bundle products and discounts on any matching main product.

- Set discounts in various ways.

- Easy to Enable/ Disable any package at anytime.

- Able to specify the period during which the package will be active.

## How to install Magento 2 Bundle Pack Extension
### ✓ Install Bundle Pack extension for Magento 2 via composer (recommend)
Run the following command in Magento 2 root folder:

```
composer require magepow/bundlepack
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```


## Bundle Pack extension Pro user guide
### Setup New Package
To create new package, please go to the `admin panel → Magepow → Bundle Pack` and click `Add New Pack` button.

![Magento 2 Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/create_rule1.png)
#### General Tab
![Magento 2 Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/general.png)
* Enable - set to Yes to make the bundle pack active.
* Enable From - specify the period during which the bundle pack will be active. The bundle will be automatically enabled and disabled on the specified date and time.
* Bundle Pack Name - define the name of a bundle pack (for internal use only).
* Stores - choose the store views to show a bundle pack for.
* Customer Groups - select customers groups to show a bundle pack for.
* Title - specify the bundle pack title that will be displayed on the products page.

![Magento 2 Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/general2.png)
* Discount Type - three discount types are available, please choose one of them from the dropdown:

  - Fixed - set 'Fixed' type of the discount to apply a discount like '$10', i.e. the fixed sum of money.

  - Percentage - set 'Percentage' type of the discount to apply a discount like 10% from the final price of the bundle pack, which means that the actual discount amount will vary from bundle to bundle.

  - Conditional Discounts - choose this option if you want to configure a differentiated discount depending on how many products are added to the cart.

* Discount Amount - specify the discount amount.
* Apply Discount to the Main Product - enable the option to apply the discount to the main product in a bundle pack.
* Apply discount if - Choose from the two available options:

  - Any Bundle Product is Chosen - the discount will be applied if any product from the bundle is chosen.

  - All Bundle Products are Chosen - the discount will be applied only if all products from the bundle are chosen.

#### Conditional Discounts Tab
This tab is only appear if you choose 'Conditional Discounts' for `Discount Type` in `General tab`.

![Magento 2 Extention Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/conditional.png)

Explanation of above settings: with 2 selected bundle products, those products will get 4 percent discount; with 3 selected bundle products, those products will also get 4 percent discount and if there are 4 or more selected bundle products, those products will get 6 percent discount.

#### Bundle Pack Products Tab
Bundle Pack Products tab when you choose 'Conditional Discounts' for `Discount Type` in `General tab`.

![Magento 2 Extention Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/bundle_product.png)

When you choose 'Fixed' or 'Percentage for `Discount Type` in `General tab`, `Conditional Discounts Tab` will not be displayed but you will able to specify discount amount of each product, if you leave it blank, the Discount Amount in the General Tab will be applied.

![Magento 2 Extention Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/bundle_product2.png)

You can choose the order of bundle pack products on the appropriate grid via drag-and-drop, this order will be displayed in the package on the customer site.

#### Main Products Tab
Choose the main products you want to display the packages.

![Magento 2 Extention Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/main_product.png)

#### Configuration
Go to the `admin panel -> Stores -> Configuration -> Magepow -> Bundle Pack`

![Magento 2 Extention Bundle Pack Pro](https://github.com/magepow/magento-2-bundle-pack/blob/main/media/configuration.png)

* Display Position - choose the position to display product bundle packs: below product info or on a product tab.

* Tab Title - when displaying bundle packs on a product tad, specify a custom title for the tab.

* Display Popup for Options Choosing - Use this setting to configure the display of the popup for choosing custom product options.

* The setting offers two ways of display:

  - Only if Product has Required Options - choose this option to show the popup only if a product has any required options to be configured.
  - Always - if set to 'Always', the popup will be displayed even if the product has only non-required options to choose from.
## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme/alopay)

**[Our Magento 2 Extensions](https://magepow.com/magento-2-extensions.html)**

* [Magento 2 Recent Sales Notification](https://magepow.com/magento-2-recent-sales-notification.html)

* [Magento 2 Categories Extension](https://magepow.com/magento-categories-extension.html)

* [Magento 2 Sticky Cart](https://magepow.com/magento-sticky-cart.html)

* [Magento 2 Ajax Contact](https://magepow.com/magento-ajax-contact-form.html)

* [Magento 2 Lazy Load](https://magepow.com/magento-lazy-load.html)

* [Magento 2 Mutil Translate](https://magepow.com/magento-multi-translate.html)

* [Magento 2 Instagram Integration](https://magepow.com/magento-2-instagram.html)

* [Magento 2 Lookbook Pin Products](https://magepow.com/lookbook-pin-products.html)

* [Magento 2 Product Slider](https://magepow.com/magento-product-slider.html)

* [Magento 2 Product Banner](https://magepow.com/magento-banner-slider.html)

**[Our Magento 2 services](https://magepow.com/magento-services.html)**

* [PSD to Magento 2 Theme Conversion](https://magepow.com/psd-to-magento-theme-conversion.html)

* [Magento 2 Speed Optimization Service](https://magepow.com/magento-speed-optimization-service.html)

* [Magento 2 Security Patch Installation](https://magepow.com/magento-security-patch-installation.html)

* [Magento 2 Website Maintenance Service](https://magepow.com/website-maintenance-service.html)

* [Magento 2 Professional Installation Service](https://magepow.com/professional-installation-service.html)

* [Magento 2 Upgrade Service](https://magepow.com/magento-upgrade-service.html)

* [Magento 2 Customization Service](https://magepow.com/customization-service.html)

* [Hire Magento 2 Developer](https://magepow.com/hire-magento-developer.html)

**[Our Magento 2 Themes](https://alothemes.com/)**

* [Expert Multipurpose Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/expert-premium-responsive-magento-2-and-1-support-rtl-magento-2-/21667789)

* [Gecko Premium Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/gecko-responsive-magento-2-theme-rtl-supported/24677410)

* [Milano Fashion Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/milano-fashion-responsive-magento-1-2-theme/12141971)

* [Electro 2 Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/electro2-premium-responsive-magento-2-rtl-supported/26875864)

* [Electro Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/electro-responsive-magento-1-2-theme/17042067)

* [Pizzaro Food responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/pizzaro-food-responsive-magento-1-2-theme/19438157)

* [Biolife organic responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/biolife-organic-food-magento-2-theme-rtl-supported/25712510)

* [Market responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/market-responsive-magento-2-theme/22997928)

* [Kuteshop responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/kuteshop-multipurpose-responsive-magento-1-2-theme/12985435)

* [Bencher - Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/bencher-responsive-magento-1-2-theme/15787772)

* [Supermarket Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/supermarket-responsive-magento-1-2-theme/18447995)
