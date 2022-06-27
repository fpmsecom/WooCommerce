Disclaimer: Please note that we no longer support older versions of SDKs and Modules. We recommend that the latest versions are used.

First Payments Woocommerce Plugin
==============

This module enables the use of https://mms.firstpayments.co.uk/ payment gateway using the Woocommerce project http://www.woothemes.com

COMPATIBILITY
------------

Compatible with version 6.4.x of Woocommerce and upto 5.9.x of Wordpress.  Untested on vesrions prior to and including 3.x of both.
Supports WooCommerce Subscriptions.

TESTING/DEMONSTRATION
------------

Testing/Non-live integration details can be provided on-request.

INTRODUCTION
------------

This module enables the woocommerce customers to pay for their items using the First Payments hosted form or direct payment gateway.

What does it do?
----------------
Presents the option to pay with credit card or debit card via the First Payments payment gateway.

DOWNLOAD
------------
Click Code from the top of this page, then Download Zip

![HowToDL](https://i.imgur.com/8JVti4N.png)

UPGRADE PRECAUTIONS
------------

As a precaution, always Deactivate any existing version(s) of the extension you are currently using BEFORE uploading a newer version to your WooCommerce store or overwriting an existing version of the extension.  Failure to do so can result in PHP errors.

INSTALLATION
------------

1. Go to the plugins section of the admin panel

2. Click Add New

3. Click Upload plugin (Near the top left of the page nexto the menu)

4. Click the "Choose File" button and select the module (which will be the whole zip file this readme is in)

4. Click the "Install Now" button and then click the "Activate" button.


Manual installation 
--------------------

1. Unzip and upload the plugin folder to your /wp-content/plugins/ directory

2. Activate the plugin through the Plugins menu in WordPress

3. Go to WooCommerce -> Settings and click on the Checkout tab. 

4. Find First Payments in the Payment Gateways section 

5. Click the settings button to configure and enable the gateway.

6. Click 'Save Changes'.


Setup Instructions
--------------------

Setting up the module requires at a minimum a merchantID, a signature/secret key and
a gateway URL i.e. https://gateway.firstpayments.co.uk to be entered in the plugin's settings.

You will then need to select an integration type to use.  We advise the Hosted Embedded option.

The module will also need to be enabled so it appears as a payment option on the checkout.
