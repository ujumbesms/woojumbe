# UjumbeSMS Woocommerce Plugin
Use this plugin to send messages to customers on you woocommerce webite. SMS notification can be sent on various statues including customer chekout, order payment, order shipment etc. You can also send messages to the site administrator to notify them of order that require attention. 

## Manual Installation

For manual installation, download a zip file from github. You can upload the file directly from your WordPress dashboard, or using an FTP application.

## Quick Overview 

To start sending out messages using this plugin, for various order statuses please configure the plugin under the woocommerce settings as shown below: 

Naviagate to woocomerce setting and click on the UjumbeSMS Settings Tab. 

![alt text](https://github.com/ujumbesms/woojumbe/blob/main/screenshots/ujumbe_settings.png?raw=true)

Add you email address and the developer API key as used in the UjumbeSMS account. Ensure to paste the details correctly. 

Scroll down to add the messages that will be sent out for checkout and order completion. 

![alt text](https://github.com/ujumbesms/woojumbe/blob/main/screenshots/messages.png?raw=true)

To create you messages, you can use any of this placeholder to depect the specific parameter withing the order. 

{SHOP_NAME} , {CURRENCY_NAME} , {ORDER_NUMBER} , {ORDER_DATE} , {ORDER_STATUS} , {ORDER_ITEMS} , {BILLING_FNAME} , {BILLING_LNAME} , {BILLING_EMAIL} , {ORDER_AMOUNT} , {CURRENT_DATE} , {CURRENT_TIME}

An example message using the above placeholder can be:

Dear {BILLING_FNAME}, thank you for shopping at {SHOP_NAME}. Your total order is  {CURRENCY_NAME} {ORDER_AMOUNT} and your delivery is underway.

## Support

For any issues/bugs/errors, please contact support@ujumbesms.co.ke. We are glad to be of any assistance.
