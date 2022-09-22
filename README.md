# wifi-smtp
Accessing client's wi-fi details including password then sending it to mail.

Run cmd on your windows machine and enter netsh wlan show profile {enter the wifi network you are currently accessing} key=clear to get the password of any wifi-network

also provides details about the wifi network that includes the security and connectivity settings that can be used to probe the network.

You can have these details delivered to your gmail account via the smptlib module.



1. smtp.SSL connections delivers to yout e-mail

![profile](https://user-images.githubusercontent.com/61822296/191806946-d0e46ce0-958b-49c1-b32e-4d64daafb43e.png)




2. SSL requires you to generate an app password

![appPassword](https://user-images.githubusercontent.com/61822296/191806969-43cfe0f9-fbb8-44a5-8a9a-aa95b7f622ad.png)


This article show how to set-up a app password for SSL functionality, however you must set two-factor authentication on your gmail -

https://devrescue.com/python-send-email-with-smtp-over-ssl/



 



