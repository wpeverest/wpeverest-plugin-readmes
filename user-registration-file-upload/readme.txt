=== User Registration File Upload ===
Contributors: WPEverest
Tags: user registration, addon, file , user registration file upload
Requires at least: 5.5
Requires PHP: 7.4
Tested up to: 6.9
Stable tag: 1.3.20
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

File upload addon for user registration plugin.

== Description ==

File upload addon for user registration plugin.

Get [free support](https://wpuserregistration.com/support/)


### Features And Options:
* File upload feature on registration form
* Download uploaded file by user
* Upload restriction for specific file type feature
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

= 1.3.20   - 02/02/2026 =
* Fix      - File upload issue on edit profile.

= 1.3.19   - 12/01/2026 =
* Enhance  - Rearrange setting into Settings > Registration Login > File Upload.

= 1.3.18   - 13/11/2025 =
* Fix      - File upload not working for Admin on  non ajax profile edit.

= 1.3.17   - 17/07/2025 =
* Enhance  - Support m4v format on file upload.

= 1.3.16   - 16/04/2025 =
* Fix      - File upload issue for mp3,csv and txt.

= 1.3.15   - 25/02/2025 =
* Fix      - File uploading twice from wp users edit page.

= 1.3.14   - 05/02/2025 =
* Dev      - Compatibility with new membership approach.
* Bug      - List all forms in global settings uploaded files tab.

= 1.3.13   - 31/07/2024
* Added    - Hook for compatiblity with Cloud Storage Addon.
* Dev      - Trigger latest pro version update for pro v4.1.4 users.

= 1.3.12   - 15/04/2024
* Tweak    - Addon update check triggered from User Registration Pro.
* Fix      - File Uploader not working on Elementor PopUps.

= 1.3.11   - 05/03/2024
* Enhance  - Addon dependency on User Registration Pro.
* Fix      - Check Plugin Update once a day.
* Fix      - Sync Issue in File Upload Field in WooCommerce Checkout Page.

= 1.3.10   - 02/01/2024
* Fix      - Profile update response is overridden by file upload response.

= 1.3.9    - 13/10/2023
* Tweak    - Changed hook to trigger for checking updates.
* Tweak    - Add filter to change file upload directory.
* Dev      - Compatibility for uploaded fields display in view user page.
* Fix      - File upload issue while updating the profile on ajax submission.

= 1.3.8    - 10/08/2023
* Tweak    - Filter to change the filename.
* Fix      - Upload error message overflow.
* Fix      - Vulnerability issue to arbitrary file upload.

= 1.3.7    - 29/06/2023
* Fix      - Security Vulnerability issue from arbitrary file upload.

= 1.3.6    - 14/06/2023
* Tweak    - Create global constant for upload dir path and url.

= 1.3.5    - 31/05/2023 =
* Tweak    - Converted to boolean.
* Fix      - Edit profile ajax enabled check.
* Fix      - Uploaded file not recognized by media library.
* Dev      - Compatibility with global search settings.

= 1.3.4    - 16/03/2023 =
* Refactor - Backend validation for form data.
* Fix      - Server side validation for max file size.
* Fix      - Form Id not found in WooCommerce checkout.
* Fix      - File type icon not visible in edit profile.

= 1.3.3    - 20/02/2023
* Refactor - File upload method.

= 1.3.2    - 06/01/2023
* Enhance  - Suppors more file type like csv,ppt,xls,xlsx.
* Fix      - File size validation message.
* Fix      - Proper validation for deleting self uploaded file.
* Fix      - Valid file not being uploaded in edit-profile page.
* Fix      - Check the file exists or not before delete the file.
* Fix 	   - Valid File Types option individual form setting not working.
* Fix      - Prevent edit profile update with prevailing file upload error.
* Fix      - Default file type validation when no file type validation set.

= 1.3.1    - 30/12/2022
* Enhance  - Dropzone buttons in edit profile page.​
* Enhance  - File listing design in user edit in wp-admin.​
* Fix      - Use ini max file size if not set.​
* Fix      - Max file size setting accepting negative values.
* Fix      - Serverside validation for valid file type.

= 1.3.0    - 06/09/2022
* Feature  - Add tooltip for file upload field label in frontend.
* Enhance  - Display icons for uploaded files according to extension.​
* Tweak    - Replace incremental file name function with WordPress default.​
* Fix      - File upload not working from admin side edit user.
* Fix      - Remove uploaded files if the user does not register.​
* Fix      - Removed file from media occupies the space in users file upload field.​

= 1.2.6    - 01/06/2022 =
* Enhance  - File upload to `user_registration_uploads/file-uploads` folder.
* Enhance  - Remove file from directory when file is removed by user.
* Enhance  - Remove file from directory when user is deleted.
* Tweak    - Incremental file name for duplicate files.

= 1.2.5    - 27/01/2022 =
* Fix      - Required issue when conditional logic enabled.

= 1.2.4    - 13/12/2021 =
* Tweak    - User Registration Pro compatibility.
* Fix 	   - Implement validation for file upload field.

= 1.2.3    - 19/10/2021 =
* Enhance  - Readonly option added.
* Enhance  - Form builder validation.

= 1.2.2    - 02/08/2021 =
* Enhance  - Reset Button in UR Form.
* Refactor - Settings page design and parsing.
* Fix      - File upload process on wp admin edit user page.
* Fix      - Class translation issue.

= 1.2.1 - 11/12/2020 =
* Tweak - Properly re-initialize file upload field to resolve no URL issue.
* Fix - Dropzone already attached issue.
* Fix - Mp3 file upload issue.

= 1.2.0 - 18/11/2020 =
* Feature - Max upload size setting for individual file upload field.
* Feature - Valid file type setting for individual file upload field.
* Enhance - File Upload field preview in the Form Builder.
* Tweak - Dropzone texts localized and made translation friendly.
* Tweak - Dropzone re-initialized on full page load.
* Tweak - Deprecate old admin notice function for compatibility with hide notice.
* Fix - File not being uploaded after wordpress 5.5.3.
* Fix - Missing attachment due to form filler extension.

= 1.1.1 - 12/08/2020 =
* Tweak - Tooltip added in the form builder.
* Fix - File upload field UI in Woocommerce checkout and my account page.
* Fix - Enqueue scripts in only UR pages

= 1.1.0 - 15/05/2020 =
* Feature - Multiple file uploads.

= 1.0.5 - 05/09/2019 =
* Tweak - Fields Icon change.

= 1.0.4 - 05/07/2019 =
* Fix - Translation in Upload File button label.

= 1.0.3 - 23/01/2019 =
* Fix - Enqueue assets globally

= 1.0.2 - 28/09/2018 =
* Feature - Download uploaded file from user profile
* Fix 	  - Description on file upload field
* Fix 	  - Required field issue even with uploaded file

= 1.0.1 - 26/06/2017 =
* Fix - File view for other file types than image.
* Feature - Download button

= 1.0.0 - 22/09/2017 =
* Initial release
