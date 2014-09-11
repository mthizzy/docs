---
layout: page
weight: 0
title: Two Factor Authentication
navigation:
  show: true
---

* Log in to your SendGrid account like normal.

* On the Account Overview page, click on Account Settings.

![]({{root_url}}/images/account_settings.png)

* On the right-hand side of the screen, click on “Setup Multifactor Authentication.”

* From the Multifactor Authentication page, enter your phone number, and click on “Send Text Message.”

* Check your phone.  You will have received a test message with a 6-digit code.  Now enter it in the “Verify Authentication Code” window.

![]({{root_url}}/images/configure_multifactor.png)

* Once you’ve entered the code and clicked “Verify,” you’ll get a message across the top of the screen that tells you “Code verification was successful.  Multifactor authentication has been enabled on your account.”

![]({{root_url}}/images/multifactor_confirmation.png)

* Now, whenever you log in to SendGrid, you’ll be prompted to enter a verification code that is sent to your phone at the time of login.