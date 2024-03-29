=== WooCommerce Cart Abandonment Recovery ===
Contributors: brainstormforce, wpcrafter
Donate link: https://www.paypal.me/BrainstormForce
Tags: woocommerce, cart abandonment, cart recovery
Requires at least: 4.4
Tested up to: 5.2
Stable tag: 1.1.6
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Recover your lost revenue. Capture email address of users on the checkout page and send follow up emails if they don't complete the purchase.

== Description ==

**It’s Time to Stop Cart Abandonments and Recover Your Lost Revenue!**

Research shows about 60% to 80% of the users who go to the checkout page, do not complete their purchase. Even the best <a href="https://wpastra.com/best-checkout-experience/" target="_blank">optimized checkout process</a> has an abandonment rate of 20%

There can be many reasons for cart abandonment.

But we have good news for you. Install our plugin and recover your lost revenue, **absolutely free**.

**How Does This Plugin Work?**

The plugin captures the email address of users on the checkout page.

If the purchase is not completed within 15 minutes, it starts sending an automated series of follow up emails that you can customize to match your brand.

Through the email series, you can: remind them to complete the purchase, ask for feedback or offer a custom discount that will entice potential buyers to complete the purchase. You can send as many emails as you would like.

Below is just an example of email sequence you can have:

* **1st email after 1 hour**: Ask if there was any technical issue.

* **2nd email after 24 hours**: Remind to complete purchase

* **3rd email after 72 hours**: Offer a unique, limited time 5% discount

**Some Amazing Features**


WooCommerce Cart Abandonment Recovery offers everything you need to recover your abandoning carts.

* **Unique Checkout Links**: Email a unique checkout link to each shopper that takes them exactly where they left off. So if a shopper had filled the checkout form, click on the unique link takes him to a prefilled checkout page. Less the friction for the shopper, and more conversions for you!

* **GDPR Compliant**:  You can optionally show a GDPR notice on the checkout page.

* **Ready templates for follow up emails**: Writing emails from scratch can be a pain. Not everyone can frame effective follow-up emails. We provide ready conversion tested email templates.

* **Webhooks**: Use a marketing automation tool like Active Campaign, Campaign Monitor, etc? This plugin integrates with all of them through webhook easily.

* **Coupon Code**: This plugin can generate limited time unique discount coupons to entice your shoppers and send them automatically via email.

* **Reports**: You get a full report of how the plugin is working behind the scenes, and recovering your lost revenue on autopilot.


**Is This Plugin Really Free? What’s the Catch?**

Absolutely. There is no catch at all. This is a 100% free gift for all WooCommerce users from our team at CartFlows.

<a href="https://cartflows.com" target="_blank">CartFlows</a> is a premium WooCommerce plugin that is used to create marketing and sales funnels. With CartFlows, you can design better checkout pages, add <a href="https://cartflows.com" target="_blank">order bump</a> or even <a href="https://cartflows.com" target="_blank">one-click upsell</a> functionality.

**Will It Affects the Performance of My WooCommerce Shop?**

No. Just as WooCommerce, this plugin stores everything locally in the database of WordPress. Emails are sent via WordPress native 'wpmail' function or SMTP. We have optimized the plugin so it leaves no performance impact.


**How Can I Get Started?**

Getting started is very easy.

* **Step 1**: Install and activate the WooCommerce Cart Abandonment Recovery plugin.

* **Step 2**: Review the default email templates. Make necessary changes if required.

* **Step 3**: You’re done!

The plugin will start recovering your lost sales in as quickly as 15 minutes.

== Installation ==

1. Upload `woocommerce-cart-abandonment-recovery.zip` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does this plugin work with CartFlows? =

Yes, of course. We have built it in a way that it will work with CartFlows as well as with WooCommerce.

= Why Follow-up emails not sent? =

Make sure to activate the email template from Follow-Up Emails >  Edit (the template) > Activate Template. Similarly, activate all required templates.

= Why incomplete order is not being considered as abandoned? =

The cart will be considered abandoned if the order is not completed in 15 minutes. You would need to start capturing abandoned carts from Settings > Enable Tracking.

= Where can I create a coupon code? =

From the Settings tab, enable webhook. It will offer you an option to create a coupon code. You can create a coupon for a specific email template as well. Just edit the template you will find an option below the editor.

= Can I display a confirmation message for GDPR? =

Yes, the plugin has GDPR integration. You can ask for permission before tracking data. The option will be available under Settings > GDPR Settings.

= How to allow the user to unsubscribe the abandoned cart notification emails? =

In the email templates, you can use `{{cart.unsubscribe}}' to add an unsubscribe link.
The plugin offers an advanced feature for admin to unsubscribe a particular user. As the admin can view the list of abandoned users, he can manually do the unsubscription.

= Can I integrate the other email services like MailerLite? =

Yes, the webhook feature will help you with this. You just need to create a webhook in the Zapier and add it from Settings tab > Webhook Settings.

== Screenshots ==

1. Track recovery report for abandonment sales from the dashboard
2. Schedule the follow-up emails from one place
3. Prebuilt and easy-to-edit Email templates
4. General settings for Email, Webhook (Coupon Code), GDPR

== Changelog ==
= Version 1.1.6 - Friday, 19th July 2019
* New: Bundled product support for email checkout URL.
* Improvement: Added phone number and address while triggering the to webhook.
* Fix: Creating tables and default settings on activation.

= Version 1.1.5 - Tuesday, 9th July 2019
* Fix: Other crons disappearing issue.

= Version 1.1.4 - Tuesday, 9th July 2019
* Fix: Follow up emails were getting sent even after the completion of the order.
* Fix: Email template variable 'Abandoned Product Names' warning issue.

= Version 1.1.3 - Thursday, 27th June 2019
* Improvement: Added checkout link for abandoned cart inside the admin section.
* Fix: Added pagination for reports.
* Fix: Recover report calculations before campaign triggers.
* Fix: Empty cart notice when CartFlows checkout is set global.

= Version 1.1.2 - Wednesday, 12th June 2019 =
* Fix: Issue of timezone while sending mail through cron.
* Fix: Delete single cart abandonment order.
* Fix: MySql 5.5 support for CURRENT_TIMESTAMP.

= Version 1.1.1 - Thursday, 06th June 2019 =
* New: Added feature to reschedule emails for Admin.
* Fix: Coupon expiry time issue.
* Fix: Email issue for a user who has an already purchased order.
* Fix: Translatable strings updated.

= Version 1.1.0 - Thursday, 30th May 2019 =
* Added a view for admin to check email status specific to the particular abandoned user.

= Version 1.0.0 - Monday, 27th May 2019 =
* Initial Release

== Upgrade Notice ==