=== User Registration Two Factor Authentication ===
Contributors: WPEverest
Tags: user registration, addon, two-factor-authentication
Requires at least: 5.5
Requires PHP: 7.4
Tested up to: 6.9
Stable tag: 1.1.7
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Two Factor Authentication addon for User Registration plugin.

== Description ==

Two Factor Authentication addon for User Registration plugin.

Get [free support](https://wpuserregistration.com/support/)

= Support Policy =

We will happily patch any confirmed bugs with this plugin, however, we will not offer support for:

1. Customisations of this plugin or any plugins it relies upon
2. Conflicts with "premium" themes from ThemeForest and similar marketplaces (due to bad practice and not being readily available to test)
3. CSS Styling (this is customisation work)

If you need help with customisation you will need to find and hire a developer capable of making the changes.

== Installation ==

To install this plugin, please refer to the guide here: [http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation)

== Changelog ==

= 1.1.7     - 22/01/2026 =
* Tweak     - Rearrange global settings placement.

= 1.1.6     - 07/10/2025 =
* Feature   - Timer on OTP Resend.

= 1.1.5     - 19/06/2025 =
* Tweak     - Positioning of otp verification button.
* Fix       - Email list not displaying after text translation.

= 1.1.4     - 27/05/2025 =
* Enhance   - Updated OTP secure login email content.

= 1.1.3     - 14/04/2025 =
* Fix       - Error message for used OTP on multiple browser.

= 1.1.2     - 25/02/2025 =
* Fix       - OTP page not showing while using login shortcode.

= 1.1.1     - 18/11/2024 =
* Fix       - Redirection after login.

= 1.1.0     - 09/09/2024 =
* Feature   - 2FA SMS OTP Verification.
* Tweak     - Added filter to send sms otp only.

= 1.0.14    - 19/08/2024
* Dev       - Compatibility with SMS verification module.

= 1.0.13    - 31/07/2024
* Enhance   - Script and styles optimization.
* Dev       - Trigger latest pro version update for pro v4.1.4 users.

= 1.0.12   - 31/05/2024 =
* Enhance  - Template made overridable from Theme.
* Tweak    - Added Filter to enforce 2fa to every existing users.

= 1.0.11   - 15/04/2024 =
* Enhance  - Addon dependency on User Registration Pro.
* Tweak    - Addon update check triggered from User Registration Pro.
* Fix      - Remember me is not working when 2 fa is enabled.
* Fix      - Redirection not working from My Account Shortcode.
* Fix      - Redirect back to previous page after login when 2fa enabled.

= 1.0.10   - 12/10/2023 =
* Tweak    - Changed hook to trigger for checking updates.
* Fix      - Fatal error due to vendor not found.
* Fix      - Email Templates not working for OTP email.

= 1.0.9    - 05/09/2023 =
* Fix      - Fatal error due to Admin class not found.

= 1.0.8    - 10/08/2023 =
* Enhance  - Option to enforce two-factor authentication validation for Non-UR registered users.
* Tweak    - Email Preview compatibility.
* Tweak    - Display error message when users try to submit with an empty OTP.
* Fix      - 404 OTP page not found.
* Fix      - Pressing Return or Enter after entering OTP was triggering resend OTP action.

= 1.0.7    - 31/05/2023 =
* Enhance  - Changed checkbox option to toggle in email settings.
* Enhance  - Hold timer for Resend OTP limit.
* Dev      - Compatibility with search global settings.
* Fix      - Role based redirection after login not working

= 1.0.6    - 26/04/2023 =
* Enhance  - Support dynamic translation for global settings.
* Fix      - Endpoint translation issue.

= 1.0.5    - 16/03/2023 =
* Tweak    - Add minutes text to otp expiry time in email.
* Fix      - Two factor authentication started when changing password.
* Fix      - Hide OTP page if two factor authentication disabled in settings.
* Fix      - Two factor authentication buttons design fix in responsive and mobile view.

= 1.0.4    - 23/02/2023 =
* Fix      - Class 'Totp' not found.

= 1.0.3    - 20/02/2023 =
* Fix      - Wrong call back function used for OTP_Email class.
* Fix      - Redirect to login or my account page from two factor authentication page.

= 1.0.2    - 09/01/2023 =
* Fix      - Classes not found during activation.
* Dev      - Add vendor folder in build zip.

= 1.0.1    - 02/01/2023 =
* Enhance  - Show hold period timer in error message.​
* Enhance  - Redirect to login page on otp submit limit hit.
* Refactor - Standardize function and variable names.
* Tweak    - Change 2FA setting tooltips.
* Tweak    - Force My Account page setup before enabling tfa.

= 1.0.0    - 10/11/2022 =
* Initial release
