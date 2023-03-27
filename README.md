# Daily Email Tester

This Wordpress plugin was inspired by a question on the /r/wordpress sub-Reddit titled [How to send an SMTP test email every day](https://www.reddit.com/r/Wordpress/comments/105zc1k/how_to_send_an_smtp_test_email_every_day/). It automatically sends a daily scheduled test email to an email address of your choosing to verify that outbound email setup works correctly. So, as a webmaster, you could set it to send you an email to your personal address: if you don't get a daily email - there's a problem. 

The plugin sets up a configuration screen at Tools > Daily Email Tester which allows:

1. Setting the email address to which test emails will be sent daily.
2. Triggering a test email manually, which is useful when initially setting up the plugin

If the debug.log is activated, the plugin will write a daily entry to it when it runs. [See here](https://deliciousbrains.com/why-use-wp-debug-log-wordpress-development/) about managing your debug.log.

The plugin was created by [nanoPost - The Wordpress Email Authority](https://nanopo.st)
