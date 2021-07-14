# UjumbeSMS WooCommerce Plugin
Use this plugin to send messages to customers on your WooCommerce website. The SMS notification can be sent on various statuses including customer checkout, order payment, order shipment, etc. You can also send messages to the site administrator to notify them of orders that require attention. 

## Manual Installation

For manual installation, download a zip file from GitHub. You can upload the file directly from your WordPress dashboard, or using an FTP application.

## Quick Overview 

To start sending out messages using this plugin, for various order statuses please configure the plugin under the WooCommerce settings as shown below: 

Navigate to WooCommerce setting and click on the UjumbeSMS Settings Tab. 

![alt text](https://github.com/ujumbesms/woojumbe/blob/main/screenshots/ujumbe_settings.png?raw=true)

Add your email address and the developer API key as used in the UjumbeSMS account. Ensure to paste the details correctly. 

Scroll down to add the messages that will be sent out for checkout and order completion. 

![alt text](https://github.com/ujumbesms/woojumbe/blob/main/screenshots/messages.png?raw=true)

To create your messages, you can use any of these placeholders to depict the specific parameter within the order. 

{SHOP_NAME} , {CURRENCY_NAME} , {ORDER_NUMBER} , {ORDER_DATE} , {ORDER_STATUS} , {ORDER_ITEMS} , {BILLING_FNAME} , {BILLING_LNAME} , {BILLING_EMAIL} , {ORDER_AMOUNT} , {CURRENT_DATE} , {CURRENT_TIME}

An example message using the above placeholders can be:

Dear {BILLING_FNAME}, thank you for shopping at {SHOP_NAME}. Your total order is  {CURRENCY_NAME} {ORDER_AMOUNT} and your delivery is underway.

## Support

For any issues/bugs/errors, please contact support@ujumbesms.co.ke. We are glad to be of any assistance.
