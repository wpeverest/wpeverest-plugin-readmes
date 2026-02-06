=== User Registration Stripe ===
Contributors: WPEverest
Tags: user registration, addon, stripe,
Requires at least: 5.5
Requires PHP: 7.2
Tested up to: 6.9
Stable tag: 1.3.15
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Stripe addon for User Registration

== Description ==

Stripe addon for user registration plugin.

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

= 1.3.15    - 07/01/2025 =
* Refactor  - Subscriptions and Payments details merged into my account tabs.
* Enhance   - My account design update.

= 1.3.14    - 13/11/2025 =
* Tweak     - Add full-name param in stripe customer creation.

= 1.3.13    - 29/10/2025 =
* Security  - Stripe payment intent verification and nonce.
* Dev       - Hook to hide the postal code in stripe.

= 1.3.12    - 27/08/2025 =
* Enhance   - Form Settings Design.

= 1.3.11    - 17/07/2025 =
* Fix       - Front spinner still showing after successful registration.

= 1.3.10    - 19/06/2025 =
* Tweak     - Lock/Unlock Stripe payment form setting when membership field is present.
* Fix       - Translation issue on payment form field.

= 1.3.9    - 16/04/2025 =
* Fix      - Stripe login script missing dependency.

= 1.3.8      - 05/02/2025 =
* Dev      - Compatibility with new membership approach.
* Fix      - Conditional logic for allowing the customer detail fields to sync for stripe.

= 1.3.7    - 16/10/2024 =
* Fix      - Text consistency.
* Fix      - Fatal error Uncaught typeError for array_filter function.

= 1.3.6    - 01/08/2024 =
* Feature  - Set exact date for subscription to end in Subscription plan field.
* Dev      - Coupon field compatibility.
* Dev      - Trigger latest pro version update for pro v4.1.4 users.

= 1.3.5    - 15/04/2024 =
* Enhance  - Allow Trail Period option for every subscription plan.
* Tweak    - Addon update check triggered from User Registration Pro.

= 1.3.4    - 05/03/2024 =
* Enhance  - Addon dependency on User Registration Pro.
* Fix      - Payment before login not working properly.

= 1.3.3    - 12/02/2024 =
*  Feature - Subscription Plan Field.
*  Feature - Generate Payment Invoice.
*  Feature - Trial Period for subscription.
*  Fix     - User registered when user not fill card details.
*  Fix     - User registered when test card number used in live mode.
*  Fix     - User are automatically approved even though there is admin approval login option.

= 1.3.2    - 13/12/2023 =
* Refactor - Payment addon dependency for stripe addon moved to pro.
* Enhance  - Display payments status in detailed.
* Enhance  - Server side validation message shown in respective fields.
* Dev      - Upgrade stripe library to make PHP 8.1 compatible.

= 1.3.1    - 13/10/2023 =
* Refactor - Handle user approval status properly.
* Refactor - Frontend field structure of stripe gateway field for compatibility with conversational forms.
* Fix      - Redirection issue after payment.

= 1.3.0    - 31/05/2023 =
* Enhance  - Changed checkbox option to toggle in global settings.
* Enhance  - Changed checkbox option to toggle in form builder.
* Dev      - Compatibility with search global settings.
* Tweak    - Compatibility with new global settings design.
* Tweak    - Compatibility with new form builder design.
* Fix      - Make Enable Stripe unchecked by default.
* Fix      - Non zero decimal currency being paid more in stripe.

= 1.2.4    - 25/04/2023 =
* Enhance  - Lock stripe gateway field if stripe keys not setup.

= 1.2.3    - 22/02/2023
* Fix      - Conditionally accept stripe payment not working.

= 1.2.2    - 02/01/2023
* Enhance  - Send email to admin after user payment success.​
* Fix      - Create customer for non-recurring payments.​
* Fix      - Critical error when no internet connection and stripe activated.​

= 1.2.1    - 10/11/2022
* Refactor - Form submit before stripe payments.
* Feature  - Resubscribe and reactivate subscription after cancellation.

= 1.2.0   - 06-09-2022 =
* Enhance - Extra fields sync with stripe while customer creation.​
* Enhance - Show tooltip in stripe gateway field label if enabled.
* Dev     - Compatibility Quantity Field for stipe.​
* Dev     - Remove unwanted backward compatibility code.​
* Fix     - Multiple submit creates multiple subscription.​

= 1.1.7   - 20-04-2022 =
* Enhance - User Defined amount support for recurring payments.
* Fix     - Stripe class redeclare issue with EVF.

= 1.1.6   - 14-03-2022 =
* Feature - Change card details from profile page.
* Fix     - Confirmation Box for cancel subscription.
* Fix     - PHP 8.0 Compatibility.

= 1.1.5    - 26-01-2022 =
* Feature  - Selection of payment method while registering.

= 1.1.4    - 22-09-2021 =
* Tweak    - Multiple choice payment field compatibility.

= 1.1.3    - 02-08-2021 =
* Refactor - Settings page design and parsing.

= 1.1.2 - 01-07-2021 =
* Fix - Submit fails while recurring payment.
* Fix - Invalid total amount while conditional logic enabled.
* Fix - Payment is done on email already exits.
* Fix - Critical Error when API key gets empty.

= 1.1.1 - 31-05-2021 =
* Enhance - Custom recurring period and fixed plan creation approach.
* Tweak   - Payment Slider Compatibility.
* Fix     - Single Item in between Multipart results zero.

= 1.1.0 - 06-04-2021 =
* Feature	- iDEAL payment integration.

= 1.0.2 - 15-02-2021 =
* Tweak		- Deprecate old admin notice function for compatibility with hide notice.
* Fix  		- Multiple Form compatibility

= 1.0.1 - 13-10-2020 =
* Feature - Conditional logic for credit card field.

= 1.0.0 - 16-07-2020 =
* Initial release
