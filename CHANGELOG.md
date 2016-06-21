=========================CHANGELOG for the ATG 10.1 Version of the Sparkred PayPal Integration Module

-	10.1-v2.1.12 - 2016-06-21

Removed mCheckoutProgressStates from CRSPayPalCardFormHandler - MSNSPRT-479


-	10.1-v2.1.11 - 2016-06-20

Added support for the Basic Auth/Capture flow, in addition to the standard Order/Auth/Capture flow - https://github.com/sparkred-insight/PayPalModule/issues/8



-	10.1-v2.1.10 - 2016-06-12

Internal code alignment with other ATG versions of this module (as much as possible) to improve supportability - https://github.com/sparkred-insight/PayPalModule/issues/9
This also brings in new features like PayPal Credit, Reference Transactions, and more!

Changing KeyManagerFactory initialization to use the default algorithm for the current JDK - AAPSRPT-394


-	10.1-v2.1.9 - 2016-05-08

Fixing bug when description field was too long - https://github.com/sparkred-insight/PayPalModule/issues/3

-	10.1-v2.1.8 - 2016-04-18

Added missing config files.


-	10.1-v2.1.7 - 2016-04-08

Code formatting and cleanup.

Merged in TLS 1.2 built-in support - PR5

