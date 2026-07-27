=== User Registration Mollie ===
Contributors: WPEverest
Tags: user registration, addon, mollie, payment gateway
Requires at least: 5.5
Requires PHP: 7.4
Tested up to: 7.0
Stable tag: 1.1.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Mollie addon for User Registration

== Description ==

Mollie payment gateway addon for user registration & membership plugin.

Get [free support](https://wpuserregistration.com/support)

= Support Policy =

We will happily patch any confirmed bugs with this plugin, however, we will not offer support for:

1. Customisations of this plugin or any plugins it relies upon
2. Conflicts with "premium" themes from ThemeForest and similar marketplaces (due to bad practice and not being readily available to test)
3. CSS Styling (this is customisation work)

If you need help with customisation you will need to find and hire a developer capable of making the changes.

== Installation ==

To install this plugin, please refer to the guide here: [http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation)

== Changelog ==

= 1.1.2    - 22/07/2026 =
* Enhance  - Allow 100% coupon on Mollie subscription.
* Enhance  - Reactivation after Membership Cancellation.
* Fix      - Cancel previous subscription on upgrade.

= 1.1.1    - 07/07/2026 =
* Fix      - User and admin email order.
* Fix      - Subscription charges the first billing cycle twice.

= 1.1.0    - 20/05/2026 =
* Fix 	   - Customer email blank in Mollie dashboard.
* Fix 	   - Old subscription not cancelled after upgrade.
* Fix 	   - Duplicate customer records on membership upgrade.
* Fix 	   - Tax breakdown absent from Mollie payment metadata.
* Fix 	   - Tax not applied to recurring Mollie billing amounts.

= 1.0.9    - 27/04/2026 =
* Enhance  - Logger structure.
* Fix      - Test key validation.
* Fix      - Remove the unknown column transaction_id for subscription table.

= 1.0.8    - 22/01/2026 =
* Fix      - Empty payment settings.
* Fix      - Form payments not working.

= 1.0.7    - 12/01/2026 =
* Feature  - Multiple Membership Purchase Model.
* Feature  - Coupon discount support in upgrade process.
* Enhance  - Payment Retry & Dunning Emails.

= 1.0.6    - 13/11/2025 =
* Enhance  - Logger interface for membership payments.

= 1.0.5   - 07/10/2025 =
* Fix     - Subscription not working for duration greater than 365 days.

= 1.0.4   - 28/08/2025 =
* Enhance - Form settings design.
* Enhance - Add more default currencies and validation for payment gateway compatibility.
* Tweak   - Membership payment setup toggle design.

= 1.0.3   - 21/07/2025 =
* Fix     - False update for version 1.0.2.

= 1.0.2   - 17/07/2025 =
* Enhance - Separate payment settings save mechanism for mollie
* Enhance - Mollie integration to membership upgrade service.
* Tweak   - Redirection to respective payment settings section.

= 1.0.1   - 19/06/2025 =
* Enhance - Mollie Webhook Integration.

= 1.0.0   - 26/05/2025 =
* Initial release
