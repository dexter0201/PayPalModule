# CHANGELOG for the ATG 11.1 Version of the Sparkred PayPal Integration Module

##	11.1-v2.1.15 - 2016-10-12
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.15

Fixing a bug that made PayPalInfo.getCurrencyCode() result in a null value.

##	11.1-v2.1.13 - 2016-08-15
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.13

Added L_LONGMESSAGE0 to PayPayStatus.errorMessage when PayPal response is not Success.

##	11.1-v2.1.12 - 2016-08-01
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.12

Removed JDBC driver, which shouldn't have been bundled with the module.
Improved shipping address handling.

##	11.1-v2.1.11 - INTERNAL ONLY

##	11.1-v2.1.10 - 2016-07-15
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.10

https://github.com/sparkred-insight/PayPalModule/issues/10

Improved Phone Number handing.


##	11.1-v2.1.9 - 2016-07-13
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.9

Fixed a field name for getting the TransactionID to be saved in the PayPalStatus

##	11.1-v2.1.8 - 2016-06-23
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.8

Added source code for the ConfirmPayPalPaymentServlet to the src included in the module.


##	11.1-v2.1.7 - 2016-06-21
https://github.com/sparkred-insight/PayPalModule/releases/tag/ATG11.1-v2.1.7

Removed mCheckoutProgressStates from CRSPayPalCardFormHandler - MSNSPRT-479

Added support for the Basic Auth/Capture flow, in addition to the standard Order/Auth/Capture flow - https://github.com/sparkred-insight/PayPalModule/issues/8



##	11.1-v2.1.6 - 2016-06-12

Internal code alignment with other ATG versions of this module (as much as possible) to improve supportability - 

##	11.1-v2.1.5 - 2016-06-10

Added support for PayPal Credit - https://github.com/sparkred-insight/PayPalModule/issues/7

Updated documentation


##	11.1-v2.1.4 - 2016-05-08

Fixing bug when description field was too long - https://github.com/sparkred-insight/PayPalModule/issues/3


##	11.1-v2.1.3 - 2016-03-22

Merged in TLS 1.2 built-in support

