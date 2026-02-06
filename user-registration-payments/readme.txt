=== User Registration Payments ===
Contributors: WPEverest
Tags: user registration, addon, registration fee, paypal, payment, gateways
Requires at least: 5.2
Requires PHP at least: 7.2
Tested up to: 6.4.2
Stable tag: 1.5.4
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Payments addon for User Registration

== Description ==

Integrates PayPal into your forms for registration fee payments, donations, and more.

Get [free support](https://wpeverest.com/support-ticket/)


### Features And Options:
* Pay for registration without directly using your credit or debit card, with connected email address.
* Donation
* Test/Sandbox Mode Acceptance
* Incredible Support
* Well Documented
* Translation ready

== Installation ==


== Frequently Asked Questions ==

= What is the plugin license? =

* This plugin is released under a GPL license.

= Does the plugin work with any WordPress themes?

Yes, the plugin is designed to work with any themes that have been coded following WordPress guidelines.

== Screenshots ==

== Changelog ==

= 1.5.4    - 12/02/2024 =
* Feature  - Subscription Plan Field.
* Feature  - Generate Payment Invoice.
* Fix 	   - Success Email sent twice when paypal subscription completed.

= 1.5.3    - 13/12/2023 =
* Refactor - Payment addon dependency for stripe addon moved to pro.
* Enhance  - Display payments status in detailed.

= 1.5.2    - 12/10/2023 =
* Refactor - Handle user approval status properly.
* Refactor - Frontend field structure of all fields for compatibility with conversational forms.
* Enhance  - Display payment details in user view page.

= 1.5.1    - 10/08/2023 =
* Tweak - Email Preview compatibility.

= 1.5.0    - 31/05/2023 =
* Feature  - Discounted price
* Refactor - Changed checkbox option to toggle in global settings.
* Refactor - Changed checkbox option to toggle in the form builder.
* Tweak    - Changed range payment slider select option to toggle.
* Tweak    - Compatibility with new global settings design.
* Tweak    - Compatibility with new form builder design.
* Fix      - Remove currency symbol from single item value.
* Fix      - Make Paypal and Stripe Default false.
* Fix      - Total value NaN when quantity empty.
* Dev      - Add filter to handle the quantity field value.
* Dev      - Compatibility with search global settings.

== 1.4.4   - 15-03-2023 =
* Refactor - Backend validation for form data.
* Fix      - Disable selected field from target field list in quantity field.

== 1.4.3   - 22-02-2023 =
* Enhance  - Support extra currencies
* Enhance  - Validations for not supported currencies.
* Fix      - Undefined index field key.

= 1.4.2    - 02/01/2023
* Enhance  - Update Quantity field icon.
* Tweak    - Update success message when no payment process after registration.
* Fix      - Add validation for price inputs in single item and multiple choice fields.
* Fix      - Add validation for Paypal Recurring Period setting input.

= 1.4.1    - 10/11/2022
* Refactor - Quantity fields initialization.
* Dev      - Resubscribe and reactivate subscription after cancellation compatibility.

= 1.4.0    - 06/09/2022 =
* Feature  - Introduce Quantity Field.​
* Feature  - Admin notification after user success payment​
* Enhance  - Update user payment status by admin.​
* Enhance  - Show tooltip for payment fields if enabled.
* Fix      - User defined single item required issue payment success but user not registered.​

= 1.3.2    - 14/07/2022 =
* Feature  - Paypal Subscription.
* Refactor - Redundant title remove.

= 1.3.1   - 14/03/2022 =
* Dev 	  - PHP 8.0 Compatibility.
* Tweak   - Design Changes.
* Fix 	  - Remove unwanted customer details from payments tab.
* Fix 	  - Paypal redirect after stripe payment completion.

= 1.3.0   - 26/01/2022 =
* Feature - Selection of payment method while registering.
* Fix     - Payment pending email not customized.
* Fix     - Invalid Total when payment before login processing.

= 1.2.1   - 19/10/2021 =
* Fix     - IPN verification and user approval status update.

= 1.2.0   - 22/09/2021 =
* Feature - Multiple choice payment field.
* Feature - Total payment field.

= 1.1.6   - 02/08/2021 =
* Refactor - Settings page design and parsing.

= 1.1.5   - 30/06/2021 =
* Fix 	  - Invalid total amount while condition logic enabled.
* Fix	  - Auto login conflicts.

= 1.1.4 - 31/05/2021 =
* Enhance - Payment slider in range field.

= 1.1.3 - 28/04/2021 =
* Fix - Smart tag value parse.

= 1.1.2 - 06/04/2021 =
* Dev - iDeal Payment compatibility.

= 1.1.1 - 18/11/2020 =
* Feature - Payment success and failed email content override for separate forms.
* Tweak - Deprecate old admin notice function for compatibility with hide notice.

= 1.1.0 - 13/10/2020 =
* Feature - Conditional Logic for single item field.

= 1.0.6 - 13/07/2020 =
* Dev - Stripe Addon Compatibility

= 1.0.5 - 18/03/2020 =
* Fix - Enable payment option value.

= 1.0.4 - 12/02/2020 =
* Enhancement - Dropdown changed to checkbox.
* Enhancement - Login option for separate forms.

= 1.0.3 - 05/09/2019 =
* Tweak - Fields Icon change.

= 1.0.2 - 11/10/2018 =
* Fix - Escaping attribute issue on conditional rules

= 1.0.1 - 11/09/2018 =
* Fix - Hook updater function on user_registration_init

= 1.0.0 - 14/08/2018 =
* Initial release
