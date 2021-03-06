=== Web Invoice - Invoicing and billing for WordPress ===
Contributors: mohanjith
Donate link: http://mohanjith.com/c/wordpress
Tags: bill, moneybookers, google checkout, alertpay, paypal, invoice, pay, online payment, send invoice, bill clients, authorize.net, credit cards, recurring billing, ARB
Requires at least: 2.6
Tested up to: 3.1.0
Stable tag: 2.1.0

Web Invoice lets you create and send web invoices and setup recurring billing for your clients.

== Description ==

Web Invoice lets WordPress and WordPress MU blog owners send itemized invoices to their clients. Ideal for web developers, SEO consultants, general contractors, or anyone with a WordPress blog and clients to bill. The plugin ties into WP's user management database to keep track of your clients and their information.

Once an invoice is created from the WP admin section, an email with a brief description and a unique link is sent to client. Clients follow the link to your blog's special invoice page, view their invoice, and pay their bill using Moneybookers, Google Checkout, AlertPay or PayPal. The control panel is very user-friendly and intuitive.

Credit card payments may be accepted via Authorize.net, MerchantPlus' NaviGate, Moneybookers, Google Checkout, AlertPay or PayPal account.  For recurring billing we have integrated Authorize.net's ARB API that will allow you to setup payment schedules along with invoices.

Some features:

* Create invoices from the WordPress control panel
* Prefill customer information using the WordPress user list
* Download invoice as PDF document
* Send invoice notifications to customers with a secured link back to the web invoice
* Send invoice reminders to customers with a secured link back to the web invoice
* Accept credit card payment via PayPal Payflow, Authorize.net, Sage Pay or MerchantPlus NaviGate
* Moneybookers, AlertPay, Google Checkout, 2Checkout or PayPal available if you don't have a credit card processing account
* Setup recurring billing using Authorize.net's ARB (Automatic Recurring Billing) feature, Google Checkout Subscriptions, PayPal, AlertPay or Moneybookers
* Force web invoice pages to be viewed in SSL mode
* Archive old invoices
* Easily use old invoices as templates for new ones
* Dynamic and intuitive user interface
* Automatically mark invoices paid via Moneybookers (Requires merchant status), AlertPay 
  (Requires merchant status), PayPal, Payflow, Payflow Pro, Sage Pay, Authorize.net or Google Checkout as paid 
* Split gateway support (Your client is given the option of choosing the preferred gateway from
  the list of gateways you support). e.g PayPal and Moneybookers
* All user interfaces are internationalized
* E-mail templates and hooks to allow you to customize the e-mails sent to your clients
* Integrate with other plugins, actions available: web_invoice_mark_as_paid, web_invoice_content_append, web_invoice_front_top, web_invoice_front_bottom, web_invoice_front_top, web_invoice_front_paid, web_invoice_front_unpaid, web_invoice_invoice_save, web_invoice_process_settings, web_invoice_display_settings, web_invoice_invoice_restart_recurring, web_invoice_invoice_pause_recurring
* Works with WordPress 3.x and WPMU 3.x

Sponsored features:

* Google Checkout support sponsored by Aaron Petz, http://aaronpetz.com
* Google Checkout subscriptions and PayPal Payflow support sponsored by Sean Ham, http://consulting.dynamisart.com
* Sage Pay support sponsored by Euan Robertson, http://euan.co.uk/
* AlertPay subscriptions support sponsored by Nathan Prescott, http://neopetsguru.com/
* 2Checkout integration and per invoice payment methods sponsored by Graffias Network, http://www.graffiasnetwork.com/

Would you like to see this plugin in other languages? Please show your interest in
the [Web Invoice community forum](http://mohanjith.com/forum/forum.php?id=1).

Web Invoice is already translated to:

* Italian (it_IT) by Dukessa
* Belarusian (be_BY) by iam, http://www.antsar.info
* Portugese (pt_BR) by André Luiz, http://andrewebmaster.com.br
* Spanish (es_ES) by Danilo Casati, http://www.e-rgonomy.com/
* Spanish, Columbian (es_CO) by Juan Salcedo
* Swedish (sv_SE) by Lena Petersson, http://designerstudion.se/
* French (fr_FR) by Aphrodite, http://mgr-artagency.com/
* German (de_DE) by Miguel, http://zwilla-research.com/

If you like this plugin please give it a good rating, and consider saying thanks, sponsoring a feature or making a donation.

Special thanks should go to [Tammie Lister](http://www.tammielister.com/) for creating the cool logo

Plug-in uses [dompdf](http://www.digitaljunkies.ca/dompdf/) to generate PDF documents.

This is a fork of [WP-Invoice](http://wordpress.org/extend/plugins/wp-invoice/), however now lot of things have changed since.

== Installation ==

1. Upload `web-invoice` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Follow set-up steps on main 'Web Invoice' page
1. To create your first invoice navigate to 'Web Invoice' -> 'New Invoice', and select the user who will be the recipient

Please see the [Web Invoice plugin home page](http://mohanjith.com/wordpress/web-invoice.html) for details.

== Frequently Asked Questions ==

1. Does this plugin support WordPress 3.x and WPMU 3.0? Yes

Please visit the [Web Invoice community forum](http://mohanjith.com/forum/forum.php?id=1) for suggestions and help.

Please visit the [Web Invoice issue tracker](http://code.google.com/p/web-invoice/issues/list) to report any bugs 
or submit feature requests.

== Screenshots ==

1. Invoice Overview
1. New Invoice Creation
1. Client Email Preview
1. Frontend Example

== Upgrade Notice ==

= 2.1.0 =
Important bug fixes; prevent checking archived invoices when check all is clicked
and also add missing address in the shipping info in the user profile.

== Changelog ==

= 2.1.1 =

* Added all available currencies
* Now you can select currencies you want to use in invoice

= 2.1.0 =

* Currency CHF added (Issue 76)
* due_date added as a template variable
* Use date_format option when available
* Fixed issue 36: separating customizations from core file
* Added a link to report missing currencies
* Fixed PayPal IPN
* Multi site network activate fix
* New logo

= 2.0.23 =

* Subscription start date issue

= 2.0.22 =

* Added missing address in the shipping info in the user profile
* Prevent checking archived invoices when check all is clicked

= 2.0.21 =

* Added Philippine Peso (PHP)

= 2.0.20 =

* Fixed issue 62: new currency (RON)
* New localization de_DE

= 2.0.19 =

* Fixed: invoice_date column not added on initial Web Invoice table creation
* Added option to hide invoice date
* Fixed: possible issue with item list table width

= 2.0.18 =

* Fixed issue 53: Can't attach a user to a Web Invoice
* Fixed issue 58: Company name in user profile not copied to shipping details
* Fixed issue 59: User details not shown when shipping details are missing
* Fixed issue 52: Add a field for the invoice date

= 2.0.17 =

* Fixed issue 50: Many strings to translate are in the default textdomain

= 2.0.15 =

* Fixed issue 46: Ques: What url do I give Paypal to restart IPN?
* Fixed issue 48: PHP error for DOMPDF - Web Invoice does not send

= 2.0.14 = 

* Fixed issue 45: ToolTip for each entry is not displayed
* Fixed issue 44: Logo / images do not work in PDF
* Fixed issue 41: PDF layout issue

= 2.0.13 =

* Fixed issue 40: Web Template Content not working 100%
* Fixed issue 18: Allow users not on primary blog if installed on Multisite

= 2.0.12 =

* Fixed issue 39: IPN (instant payment notification) errors from Paypal after invoice is paid

= 2.0.11 =
* Fixed issue 34: Handle users using PHP4 gracefully
* Fixed issue 35: HTML table was blowing out on my pdf

= 2.0.10 =
* Fixed issue 33: Moneybookers subscriptions fail

= 2.0.9 =
* Spanish update
* Fixed issue 32: 2CO Settings are not hidden when it's not used

= 2.0.8 =
* Fixed issue 26: "Same As Billing" does not copy country
* Fixed issue 27: "Tax" field seems to have control characters in it. e.g. "s:4:" or "s:0:"
* Fixed issue 28: Web/HTML Invoice Template
* Fixed issue 29: Tabbed settings and templates page
* Fixed issue 31: Per invoice payment options
* Support payments via 2Checkout
* Fixed issue 9: Partial payments on an invoice

= 2.0.7 =
* Fixed issue 22: PayPal recurring payments
* Fixed issue 24: Not all date strings are localized
* Fixed issue 25: Duplicate content on invoice page

= 2.0.6 =
* Fixed issue 21: Call to undefined function sys_get_temp_dir()
* Fixed issue 20: Persistent Invoice Sorting
* Fixed issue 19: Check memory available and warn user before running out of memory

= 2.0.5 =
* Fixed issue 17: Invalid argument supplied for foreach()

= 2.0.4 =
* Slashing issue in from name in mails
* Fixed issue 2: logo implementation for pdf
* Fixed issue 7: Attach PDF invoice to e-mail
* Fixed issue 5: Email 'From' Error
* Fixed issue 11: Bug in add user dropdown on add new invoice page
* Fixed issue 6: Users missing in Drop Down list
* Fixed issue 10: Date of transaction in admin overview page
* French localization
* Fixed issue 14: Add new invoice button on Invoice overview page
* Fixed issue 4: Support for multiple tax

= 2.0.3 =
* Invoice page bug fix

= 2.0.2 =
* PDF UTF support
* Swedish localization
* Multiple Tax rates
* WPMU Receipt e-mail issue

= 2.0.1 =
* Fixed; values greather than 1000 (ones with 1000 seperator) of some currencies are truncated. 

= 2.0.0 =
* Compatibility with WPMU
* PDF permission issue - take 2
* Select correct charset (inherit from Wordpress) when creating tables
* WordPress 3.0 compatibility
* PayPal IPN

= 1.12.15 =
* SagePay VendorEMail added
* Possible fix for redirect to SSL after payment issue 

= 1.12.14 =
* Google Checkout XML error when amount is greater than 1000

= 1.12.13 =
* Localized missed phrases ('Quantity', 'Tax', 'Invoice Total'). Thanks Martin Kamensky.

= 1.12.12 =
* Fixing amounts greater than 1000 shown inaccurately
* Item description in PDF was too tiny

= 1.12.11 =
* Fix recurring billing layout
* Imrove PDF layout
* Move money formatting to locale

= 1.12.10 =
* New display property profileEndDate

= 1.12.9 =
* Moved invoice history bellow rest of invoice content

= 1.12.8 =
* Record start date when a recurring payment starts
* Not set the Profile start date to current date when updating Payflow profiles
* Fixed Authorize.net issues

= 1.12.7 =
* Added new hooks/actions web_invoice_invoice_pause_recurring and web_invoice_invoice_restart_recurring

= 1.12.6 =
* Pause and recurring PayPal Payflow Pro profiles
* Update shipping details on recurring PayPal Payflo Pro profiles

= 1.12.5 =
* Google Checkout UK VAT issue
* DOMPDF EUR work around (€ displayed as ?)

= 1.12.4 =
* Added variables invoice_id and invoice_hash to e-mail templates

= 1.12.3 =
* Changed date formats for en_US and en_GB
* Changed 'Bill To' and 'Bill From' to 'Invoice From' and 'Invoice To'

= 1.12.2 =
* More improvements to invoice layout

= 1.12.1 =
* HTML Syntax issue (missed closing tag)

= 1.12.0 =
* Much awaited download invoice as PDF

= 1.11.14 =
* Update Payflow Pro recurring profiles when invoice is updated
* Cancel Payflow Pro recurring profiles when invoice is deleted

= 1.11.13 =
* Website Payments Pro HTTPS interface headers
* Load archived invoices via AJAX

= 1.11.12 =
* Bug fix

= 1.11.11 =
* PayPal Website Payments Pro Payflow Edition bug fixes 

= 1.11.10 =
* Added experimental PayPal Website Payments Pro Payflow Edition support

= 1.11.9 =
* SagePay issue, state

= 1.11.8 =
* Do not show ugly PHP error when associated user is deleted

= 1.11.7 =
* AlertPay recurring payment
* Allow non privileged users to create invoices for self
* PayPal yearly invoice fix
* Fix for some settings when localized

= 1.11.6 =
* Portugese (Brazil) localization

= 1.11.5 =
* Work around notorious plugins that include their own version of jQuery

= 1.11.4 =
* Hide State when not required

= 1.11.3 =
* Fixed IE js issues

= 1.11.2 =
* Redirect to correct invoice when the Sage Pay transaction fails

= 1.11.1 =
* Upgrading leaves payment table schema out of sync

= 1.11.0 =
* Fixed missing HTML end tags and moved autocomplete="off" to js (Better standard compliance)
* Experimental Sage Pay Form support

= 1.10.10 =
* Shipping details added to user profile

= 1.10.9 =
* Fixed typo
* Graduated PayPal recurring billing to production ready

= 1.10.8 =
* PayPal payflow pro shipping details

= 1.10.7 =
* PayPal payflow pro mark invoice as paid bug fix.

= 1.10.6 =
* Added new actions (web_invoice_invoice_save, web_invoice_process_settings, and web_invoice_display_settings)

= 1.10.5 =
* Fixed Google Checkout tax state issue

= 1.10.4 =
* PayPal Payflow Pro support
* Automatic Payflow Recurring profile creation

= 1.10.3 =
* Recurring payments with PayPal

= 1.10.2 =
* PayPal Payflow support is production ready (upgraded from experimental)

= 1.10.1 =
* Bug fixes, Google Checkout mark invoice as paid (2nd Level integration)
* Google Checkout Subscription (recurring) support
* PayPal Payflow support (experimental)

= 1.9.22 =
* Bug fixes, more permission issues in new installations

= 1.9.21 =
* Bug fixes, permission issue in new installations

= 1.9.20 =
* Capabilities based authentication

= 1.9.19 =
* Use wp_dropdown_roles to list the roles (Makes Web Invoice compatible with Capabilities Manager plugin)

= 1.9.18 =
* More actions to integrate with other plugins 

= 1.9.17 =
* Strip slashes when displaying invoice
* List user invoices under Profile
* Do not list create invoice under Profile for users who lack permission to create invoices

= 1.9.16 =
* Send itemised invoices to Google Checkout
* Small improvements to print view (as suggested by nv1962)

= 1.9.15 =
* Mark recurring invoices as paid
* Send reminders for recurring invoices

= 1.9.14 =
* New Moneybookers IPs

= 1.9.13 =
* Bug fix

= 1.9.12 =
* Other/Bank as payment option
* Show billing billing details

= 1.9.11 =
* Bug fixes

= 1.9.10 =
* Localized to Belarusian
* Moneybookers recurring payment bug fix

= 1.9.9 =
* Localized to Italian
* Company name and Tax ID as user information
* Billing Tax ID
* Display Billing Phone and TAX ID

= 1.9.8 =
* Moneybookers recurring payment IPN bug fix

= 1.9.7 =
* IP verification bug fix (Moneybookers and AlertPay)

= 1.9.6 =
* Bug fixes

= 1.9.5 =
* Secure URLs to payment method logos
* Separate address/username for Moneybookers recurring payments

= 1.9.4 =
* Tested with WordPress 2.8.4
* Compatibility with MySQL 4.0.x

= 1.9.3 =
* Fixed javascript error outside of invoice page

= 1.9.2 =
* Usability fixes

= 1.9.1 =
* Re-released because the payment forms used Google Checkout sandbox

= 1.9.0 =
* Google Checkout support

= 1.8.0 =
* Compatibility with WordPress 2.8.0
* Upgrade jquery.calculation, jquery.delegate, jquery.field and jquery.form to latest available

= 1.7.5 =
* IE not showing payment forms
* Updating invoice forces the invoice data cache to purge
* Add support for WP Mail SMTP (wp_mail)

= 1.7.4 =
* Bug fixes

= 1.7.3 =
* Bug fixes

= 1.7.2 =
* Call to undefined function web_invoice_curpageurl when CC is enabled

= 1.7.1 =
* Added database table health status
* Activation and Deactivation hooks may not have fired if
  the plugin directory is symlinked

= 1.7.0 =
* States are no longer selectable (it's just a text box)
* AlertPay API bug fix
* AlertPay IP range added (more security)
* AlertPay country code (ISO_3166-1 alpha-3 country code) to ISO_3166-1 alpha-2 country code mapping
* Allow just the button payments for PayPal
* E-mail templates
* E-mail hooks (add you own variables via another plugin)

= 1.6.3 =
* Moneybookers API tested thoroughly (Thank you MB for the test account)
* Receipt e-mail made more meaning full
* Amount decimal points fixed (using number_format)
* Dates and number formatting internationalized

= 1.6.2 =
* Formatting issue in invoice display

= 1.6.1 =
* Show unit price when displaying quantity. Change cost to the product of quantity and unti price
* Use css label missing

= 1.6.0 =
* Moneybookers recurring billing support

= 1.5.4 =
* Currency symbol shown as html entity in the mailed invoice
* MB API interop fix

= 1.5.3 =
* Fixed issue with street address, phone number and country of clients
  being reset every upgrade.
* Bug fixes (Due date)

= 1.5.2 =
* Fixed display issue with MB

= 1.5.1 =
* Added translations for en, en_US, en_GB
* Fixed issue with Moneybookers when there are more than 5 items
  and itemized details are sent to MB.
* Fixed issue with negative quantity or price in any payment
  processor

= 1.5.0 =
* Internationalization

= 1.4.0 =
* Split Gateway support

= 1.3.0 =
* Add support for AlertPay
* Support AlertPay IPN (Similar to PayPal IPN)

= 1.2.4 =
* Corrected typo (Reciept => Receipt)

= 1.2.3 =
* Moneybookers API bug fixes (Using POST instead of GET)

= 1.2.2 =
* Better debugging for Moneybookers API
* Send reminders
* Bug fixes from 1.2.1

= 1.2.1 =
* Bug fixes from 1.2.0

= 1.2.0 =
* Support Moneybookers API (Similar to PayPal IPN)

= 1.1.2 =
* Made compatible with PHP4

= 1.1.1 =
* Made compatible with PHP4
* When the invoice doesn't save, the MySQL error code is given along with
  other information.
* Bug fixes from 1.1.0

= 1.1.0 =
* Using SQL to find the invoice id from the md5 hash
* Improved SQL queries for efficiency
* Halved number of queries

= 1.0.0 =
* Initial release
