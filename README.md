# Wordpress-Facebook-Subscriber
Adds a button to your Wordpress site's shortcodes, allowing users to connect to Facebook and add their email to a list.

## How to use:
1. Connect to your Wordpress server for file transfer.
2. Unzip the plugin and copy the "facebook-email-button" folder into your Wordpress installations "plugins" directory (probably located at "/var/www/html/wp-content/plugins").
3. On your Wordpress website, log in and navigate to your Plugins page on your Dashboard.
4. Click "Activate" on the "Facebook Email Subscriber" plugin.
5. Go to the "FB Subscriber Settings" menu item under "Settings".
6. On Facebook, make sure that your Facebook app has its Site URL filled in to the base URL of the your Wordpress site.
7. Back on Wordpress, put your Facebook app's ID and secret into the "Facebook App ID" and "Facebook App Secret" fields, respectively.
8. On any page, write the shortcode "[fb-subscriber-button]" and your button will appear to anyone who visits that page.
9. Anyone who clicks the button will be asked to log in to Facebook and connect with the app.  They will then will be redirected back and registered into your database.
10. To remove themselves from the list, they simply click the button again, which should say "Unsubscribe" when they hover over it.
11. To view the most recent email addresses, go to "Facebook Subscriber List" on your dashboard.  This page also allows you to download the files as a CSV file.
