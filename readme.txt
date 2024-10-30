=== Max Spend Limit Per User For Woocommerce ===
Contributors: cheapwebdesigner
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FDYVA3GMZDTVG&source=url
Tags: woocommerce spend limit, control user's spending, woo spending by rolling days, woo spending limits per period
Requires at least: 3.0.1
Tested up to: 6.2
Stable tag: 1.0.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

== Description ==
Max Spend Limit Per User for Woocommerce is a powerful plugin that allows you to set a maximum spending limit for customers on your website. It helps you control and manage your user spending on your WooCommerce store, ensuring that they stay within their allocated budget throughout a defined period. 

Please Note: that customers are unable to modify their spending limits. Additionally, it's important to mention that the plugin does not currently provide real-time spending limit notifications. For instance, if a user has already spent $90 out of a $100 limit within a 30-day period and attempts to make a purchase of $50 within the same 30 days period, the plugin allows the checkout process to proceed. However, please be aware that after the order is placed, the customer will not be able to make any new orders until the spending limit is reset or increased by the store owner.


== Key Features ==

1. Set Maximum Spend Amount: Easily define the maximum spend amount for individual users using custom fields in their user profiles. This allows you to tailor spending limits to meet the unique requirements of each user.

2. Flexible Time Periods: Specify the spend limit period in days, allowing you to define the timeframe within which the spending is monitored. This enables you to enforce spending limits over specific durations, such as monthly, weekly, or custom periods.

3. Real-time Spending Monitoring: The plugin continuously tracks the total amount spent by users within the specified time period. It includes orders with completed, processing, and on-hold status in the calculation, providing an accurate overview of user spending. (We will include the control of order status that count towards the spending limits in the next update.)

4. Notification System: When a user reaches or surpasses their maximum spend limit, the plugin displays a notice during the checkout process. Users are promptly notified of their spending status, encouraging them to take appropriate action.

5. Contact Information: The error message includes a call to action, prompting users to get in touch with you for assistance in extending their spending limit. This provides a seamless way for users to request additional budgets or discuss their specific needs.

6. If a user has already reached or exceeded their maximum spending limit, the plugin intelligently hides the payment options, billing section, and order review section during the checkout process. This proactive measure ensures that users cannot proceed with placing an order, effectively preventing any potential overspending and promoting responsible financial management.

7. User-friendly Interface: The plugin integrates seamlessly with the WooCommerce user profile page, allowing the admin to easily view and modify the user's maximum spend amount and spend limit period. This ensures a smooth user experience and promotes transparency.


== Why it's Useful ==
1. Personalised Budget Control: Establishing individual spending limits allows you to provide tailored budget allocation for each user, meeting their unique requirements and ensuring fairness.

2. Precise Spending Management: By tracking the total amount spent by each user throughout the specified period, you gain precise control over user expenditures, promoting financial stability for your WooCommerce store.

3. Proactive User Engagement: The plugin's real-time notifications encourage users to proactively manage their spending and engage with your support team to extend their spending limit, fostering a positive user experience.

4. Enhanced Customer Satisfaction: By providing users with clear spending guidelines and personalized support, you enhance their shopping experience and foster trust in your brand.

== How To Use ==
1. Install and Activate the Plugin: Begin by installing the "Woo Max Spend Limit" plugin from the WordPress repository. Once installed, activate the plugin to start using its features.

2. Set Maximum Spend Limit: After activation, navigate to the user's profile in the WordPress admin area. You'll find new fields titled "Maximum Spend Amount" and "Spend Limit Period" under the "Max Spend Limit" section. Enter the maximum amount a user can spend within a specific time period, you have to use amount of days in the Spend Limit Period field

Save User Profile Changes: Once you've set the maximum spend amount and spend limit period for a user, save the changes made to their profile. This ensures that the limits are applied to the user's account.

== Installation ==

1. Unzip downloaded folder and upload it to 'wp-content/plugins/' folder
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Users and you will see new fields added under "Max Spend Limit" section..

== Frequently Asked Questions ==
1. Can users modify their spending limits?
No, the spending limits set by the store admin cannot be modified by the users themselves. Only the store admin has the authority to adjust the spending limits for individual users.

2. Does the plugin provide real-time spending limit notifications?
Currently, the plugin does not provide real-time spending limit notifications. The spending limits are enforced at the checkout process based on the user's previous order history within the specified time period.

3. What happens if a user exceeds their spending limit during checkout?
If a user exceeds their spending limit, the plugin takes action by hiding payment options, billing sections, and the order review section. This prevents the user from placing an order that exceeds their limit.

4. Can users place new orders once they have reached their spending limit?
No, once a user has reached their spending limit, they will not be able to place any new orders until their spending limit is reset or increased by the store admin.

5. How can a user request an increase in their spending limit?
To request an increase in their spending limit, users are advised to contact the store for further assistance. The store admin can then evaluate the request and make adjustments to the user's spending limit if deemed appropriate.

6. Is it possible to set different spending limits for different users?
Yes, the plugin allows you to set individual spending limits for each user. This provides flexibility in customizing the spending limits based on specific user requirements.

7. Can the spending limit period be customised?
Yes, the spending limit period can be customised according to your preference. You can set it to a specific number of days that aligns with your business needs, such as a week, a month, or any other desired duration.



== Changelog ==
**1.0 [2023-07-08]**
* Initial Release