# OcStore or Opencart 2.x plugin to accept Bitcoins

Requires PHP at least: 5.2
License: GPLv2 or later

## Description

Use the Apirone plugin to receive payments in Bitcoins from all around the world. We support Bitcoin SegWit protocol which has priority on the network and lower fees.

This ocStore/ OpenCart 2.x plugin accepts Bitcoins from customer and forward them to the shop owner�s wallet.
We support Bitcoin SegWit protocol which has priority on the network and lower fees.

The plugin shows the price of the items in BTC and fiat money converted into bitcoin. The merchant receives only bitcoins.
Debug mode saving all responses, debugging messages to errors logs, but it is not recommended to enable this option unless you are having issues with the plugin.
"Minimum confirmations count" is a count of Bitcoin network payment confirmations. Recommend 3, minimum 1 conf. Default value is 1.


Key features:

* We transfer your payment directly into your bitcoin wallet ( we do not hold client money)
* You do not need to complete a KYC/Documentation to start using our plugin. No third-party accounts during the process, use your own wallet.
* We will charge a fixed fee (0.0002 BTC/transaction) which does not depend on the amount of the order. No fee for amounts less than 100,000 Satoshi.
* White label processing (your online store accepts payments without redirects, iframes, advertisements, logo, etc.)
* There is no restriction on the customer's country of residence. This plugins works well all over the world.
* We support the Tor network
* You can create unlimited number of requests. 


## Installation

* Check ocStore FTP configuration in Admin panel: System � Settings click Edit button and click FTP tab. Enter FTP Host, Port, Username, Password, Root directory (FTP Root). In Enable FTP choose Yes radio button. Don't forget to save.

* Download plugin release to accept Bitcoins: https://github.com/Apirone/ocstore/releases/download/bitcoin_plugin/apirone-ocstore.ocmod.zip

1) In admin panel, go to Extensions � Extension Installer. Click Upload, choose apirone-opencart.ocmod.zip from your computer, then click Continue (if the upload gets stuck half way, please check this page for solutions).

2) Enable apirone payment extension:
For ocStore 2.0 - 2.2 version: in admin panel, go to Extensions � Payments find bitcoin via apirone and click Install button.
For ocStore 2.3.* version: in admin panel, go to Extensions, from dropdown form choose Payments, find bitcoin via apirone and click Install button.

3) Enter your bitcoin address and configure other extension settings:
For ocStore 2.0 - 2.2 version: in admin panel, go to Extensions � Payments find bitcoin via apirone and click Edit button. Do't forget to save.
For ocStore 2.3.* version: in admin panel, go to Extensions, from dropdown form choose Payments, find bitcoin via apirone and click Edit button. Don't forget to save.



## Frequently Asked Questions


#### I will get money in USD, EUR, CAD, JPY, RUR...?

No. You will get bitcoins only. Customer sends bitcoins and we forward it to your wallet.
You can enter bitcoin address of your account of any trading platform and convert bitcoins to fiat money at any time.


#### How can The Store cancel order and return bitcoins?

This process is fully manual because you will get all payments to your wallet. And only you control your money.
Contact with the Customer, ask address and finish the deal.

Bitcoin protocol has not refunds, chargebacks or transaction cancellations.


#### Fee

A fixed rate fee 0.0002 BTC per transaction, regardless of the amount and the number of transactions. Accept bitcoins for million dollars and pay the fixed fee.
We do not take the fee from amounts less than 100,000 Satoshi.