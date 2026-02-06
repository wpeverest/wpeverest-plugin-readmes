=== User Registration Customize My Account ===
Contributors: WPEverest
Tags: user registration, addon, customize my account,
Requires at least: 5.5
Requires PHP at least: 7.4
Tested up to: 6.9
Stable tag: 1.2.14
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Customize My Account addon for User Registration

== Description ==

Customize my account addon for user registration plugin.

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

= 1.2.14   - 30/01/2026 =
* Fix      - Endpoint arrangement.

= 1.2.13   - 15/01/2026 =
* Enhance  - Compatibility with updated my account design.

= 1.2.12   - 12/01/2026 =
* Enhance  - Rearrange settings placement.

= 1.2.11   - 10/07/2025 =
* Feature  - Add payment methods endpoint from WooCommerce in my account page.

= 1.2.10   - 05/09/2025 =
* Fix  	   - Critical error while visiting my account page.

= 1.2.9    - 04/09/2025 =
* Fix  	   - Margin issue in design.
* Fix      - Padding issue in design.
* Fix      - Heading color not changing.
* Dev      - Hook to modify the disable logout confirmation option.

= 1.2.8    - 16/04/2025 =
* Enhance  - Option to restrict allow endpoint.
* Enhance  - Added allow endpoint by roles option.
* Fix      - Confusing text in customize my account
* Fix      - Disable user logout link in case of customizer preview
* Fix      - Critical uncaught error type error with style customizer.

= 1.2.7    - 25/02/2025 =
* Enhance  - Updated SCSS PHP Compiler.
* Fix      - Logout popup confirmation not appearing.

= 1.2.6    - 05/02/2025 =
* Enhance  - Added membership tab support.
* Enhance  - Update on scss.php for increase in specificity of selectors.
* Dev      - Properly check module activation.

= 1.2.5    - 18/11/2024 =
* Fix      - Customizer control overflow.
* Fix      - WP Colorpicker issue conflicting customizer load.
* Dev      - Trigger latest pro version update for pro v4.1.4 users.

= 1.2.4    - 15/04/2024 =
* Tweak    - Addon update check triggered from User Registration Pro.
* Fix      - Payment endpoint Issue.
* Fix      - Logout Redirect not working properly from My Account Logout.
* Fix      - View Order redirected to default endpoint when default endpoint had content overridden.
* Fix      - My Account Redirection not working when default endpoint is disabled and Permalink Structure is custom.

= 1.2.3    - 05/03/2024 =
* Enhance  - Addon dependency on User Registration Pro.
* Fix      - Check Plugin Update once a day.

= 1.2.2   - 02/01/2024
* Enhance - Edit default dashboard content.
* Tweak   - Settings label changes for user's convenience.
* Tweak   - Design changes to make endpoint options tweak area wider.
* Fix     - Myaccount Endpoint Translation issue.

= 1.2.1    - 11/12/2023 =
* Enhance  - Custom content postition settings.
* Tweak    - Added filter before outputting endpoint content.
* Fix      - Redirection of hidden or disabled endpoint.

= 1.2.0    - 31/05/2023 =
* Enhance  - Support for link endpoint translation.
* Enhance  - Link type selector in link endpoint settings.
* Enhance  - Changed checkbox option to toggle in settings.
* Dev      - Compatibility with search global settings.
* Dev      - Compatibility for Privacy Tab.
* Tweak    - Compatibility with new global settings design.
* Fix      - Elementor issue with dashboard endpoint.
* Fix      - Override content not working on logout confirmation.

= 1.1.9    - 02/01/2023
* Fix      - Too Many Redirect issue when all endpoint disabled.​
* Fix      - Private Notes end point not showing issue

= 1.1.8    - 10/11/2022
* Fix      - Disabled endpoint displayed in classic block.

= 1.1.7    - 06/09/2022
* Feature  - Parse smart tags in endpoint content.

= 1.1.6    - 08/06/2022 =
* Fix 	   - Latin character support for Endpoint label.
* Fix      - Display icon label instead of [object] [object].
* Dev      - Check if the url is encoded.
* Dev 	   - Private notes compatibility.
* Dev 	   - Content added through action hook.

= 1.1.5    - 14/03/2022 =
* Fix 	   - My Account Endpoints Translation Issue.
* Fix  	   - Woocommerce view subscription compatibility.
* Fix 	   - New endpoints couldn't be added.
* Fix 	   - Hide save button in advance settings.

= 1.1.4    - 13/12/2021 =
* Tweak    - User Registration Pro compatibility.
* Fix 	   - Customize myaccount page design.

= 1.1.3    - 02-08-2021 =
* Enhance  - Reset to default value button added.
* Refactor - Settings page design and parsing.
* Tweak    - Enqueued wp color picker alpha globally in core.
* Tweak    - Sweetalert2 icon.

= 1.1.2 - 31-05-2021 =
* Feature - Link as a tab in my account page.
* Fix     - Override content conflict with user created endpoint.

= 1.1.1 - 06-04-2021 =
* Feature - Enable endpoint content override.
* Tweak	  - Handle deprecated jQuery methods.

= 1.1.0 - 12-01-2021 =
* Feature - Customizer for customizing styles in my account page.
* Feature - Delete Account endpoint support.

= 1.0.2 - 18-11-2020 =
* Tweak - Deprecate old admin notice function for compatibility with hide notice.
* Tweak - Add endpoint popup UI.

= 1.0.1 - 13-07-2020 =
* Feature - Woocommerce subscription and membership support
* Feature - User registration payments support
* Tweak - Toggle switch HTML
* Fix - Endpoint restrict to user role
* Fix - Endpoint duplication

= 1.0.0 - 09-04-2020 =
* Initial release
