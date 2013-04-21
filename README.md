# Can't parse emails

[RFC5322](https://tools.ietf.org/html/rfc5322#section-3.4.1) allows the usage of `+` in e-mails.

All mail that is sent to user+foo@example.com, user+bar@example.com ends up in user@example.com mailbox.
This helps managing your inbox, is extremely useful if you want to detect a service that sells user
e-mails to spammers and just keeps yourself more secure.

Some services don’t support this practice, though.

Here's a list of webservices that has no idea how to validate an email address properly
or just prohibits this feature for whatever reasons.

Hall of shame if you will.

![](https://dl.dropboxusercontent.com/u/8663332/meetup-fail.png)

## Services

* http://jobvite.com/
* http://kobobooks.com/
* http://meetup.com/
* http://oscaro.com/
* http://pornhub.com/
* http://vk.com/
