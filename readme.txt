Contact form 7 To Power Automate
==================================

MAINTAINER NEEDED. Please email me if you're interested.

-   Tags: contact form 7,cf7 api,contact form 7 remote, Contact form 7, contact form 7 integration,contact form 7 integrations, contact
    form 7 rest api,
-   Requires at least: 4.7.0
-   Tested up to: 5.9.2
-   Stable tag: 1.0.0
-   License: GPLv3 or later
-   License URI: <http://www.gnu.org/licenses/gpl-3.0.html>

An addon to transmit contact form 7 entries to Power Automate via POST request.

Description
-----------

Adds an option to send form data to a Microsoft Power Automate end point via JSON
NOTE: This plugin requires Contact Form 7 version 4.2 or later.

-   Supports JSON

Usage
-----

Simply go to your form settings, choose the "Power Automate" tab and
set your required parameters,

1.  Chose if the specific form will have it details sent to Power Automate
2.  Type the API url
3.  map the form fields (Each field that you use on the form will be
    availble on this tab after saving the form)

Installation
------------

Installing Contact form 7 TO API can be done either by searching for
"Contact form 7 TO API" via the "Plugins \> Add New" screen in your
WordPress dashboard, or by using the following steps:

1.  Download the plugin via WordPress.org.
2.  Upload the ZIP file through the "Plugins" \> Add New \> Upload
    screen in your WordPress dashboard.
3.  Activate the plugin through the 'Plugins' menu in WordPress
4.  Visit the settings screen and configure, as desired.

Frequently Asked Questions
--------------------------

= How can i redirect the user after success ? =
You can use another plugin for that - Contact Form 7 Redirection

<https://wordpress.org/plugins/wpcf7-redirect/>

### How can i set Extra parameters?

You could set hidden fields for that

<https://contactform7.com/hidden-field/>

OR

simply append the constant parameters to the url
For example:

<http://my-api-url?const1=some_value&const2=some_value>

Changelog
---------
### 1.0.0

-   Initial release.
