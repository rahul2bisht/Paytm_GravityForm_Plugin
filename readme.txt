=== Paytm Form Payment Gateway for Gravity Forms ===

Tags: ecommerce, payment gateway, wordpress, gravity forms
Requires at least: 3.5
Tested up to: 5.1
Stable tag: 1.0.1


Paytm Server Gateway for accepting payments on your Gravity Forms Store.

== Description ==

The Paytm Payment system provides a secure, simple means of authorizing credit and debit card transactions from your website.

The Sage Pay system provides a straightforward payment interface for the customer, and takes complete responsibility for the online transaction, including the collection and encrypted storage of credit and debit card details, eliminating the security implications of holding such sensitive information on your own servers. 

So this plugin helps you to accept payments with Gravity Forms using PAccounts.


== Installation ==

1. Copy the paytm-gravityforms folder into your plugin directory at `/wp-content/plugins/`.
2. Activate the plugin through the 'Plugins' menu in WordPress Administration.

== Configuration ==
1. Login to the admin panel. Browse through till Downloads->Settings->Payment Gateways tab. 
2. Scroll down to "Login and Pay with Paytm Settings"
3. Fill in the necessary details for Merchant Id, Merchant Key, Select Mode, Website Name and Industry Type.
4. Save the data.

# Paytm PG URL Details
	staging	
		Transaction URL             => https://securegw-stage.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw-stage.paytm.in/merchant-status/getTxnStatus

	Production
		Transaction URL             => https://securegw.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw.paytm.in/merchant-status/getTxnStatus
