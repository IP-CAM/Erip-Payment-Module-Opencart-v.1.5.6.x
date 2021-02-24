## Payment module through the calculation system (ERIP) for OpenCart 1.5

This module provides information interaction between your online store, the calculation system (ERIP) and payment service [BEPAID.BY] (https://bepaid.by)

### Installation

* Create a backup of your store and database
* Download the [OpenCart-Payment-Module.zip] module file (https://github.com/begateway/opencart-payment-module/raw/master/opencart-erip-payment-module.zip)
* Load the contents of the archive to your installed opencart copy
* Set the calculation (ERIP) in the module settings:
  * Store ID
  * Shop key
  * Domain API.
  * Erip Services Code
  * Order status in case of successful payment
  * Turn on the module
  * Optionally, set the module identifier to sort it in the list of payment methods. Lower value raises the module to up the list

### Notes

Developed and tested with OpenCart v.1.5.6.4

PHP 5+ required

### Test data

You can use the following data to customize the payment method in
Test mode:

  * Store Identification __363__
  * Shop secret key __4f585d2709776e53d080f36872fd1b63b700733e7624dfcadd057296daa37df6__
  * Domain API __API.BEPAID.BY__
  * Erip Services code __99999999__

In the event of a successful interaction of the online store and bepaid.by, the Buyer will show an instruction how to pay for the order through the Calculation system (ERIP) and BEPAID.BY after 10 seconds will be confirmed about the successful payment and OpenCart will transfer the order to the specified status of a successful payment.

## found a mistake or do you have an offer to improve the module?

Create [Request] (https://github.com/begateway/opencart-payment-module/issues/new) 
