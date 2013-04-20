# Can't parse emails

[RFC2822](http://tools.ietf.org/html/rfc2822#section-3.4.1) allows using “+” in e-mails.

All mail that is sent on user+1@example.com, user+2@example.com will appear in user@example.com mail.
This is extremely useful if you want to detect a service that sells user e-mails to spammers and
just keeps yourself more secure.

Some services don’t support this practice, though.

Here's a list of webservices that have no idea how to validate an email address properly.
Hall of shame if you will.

![](https://dl.dropboxusercontent.com/u/8663332/meetup-fail.png)

## Services

* http://meetup.com
* http://vk.com
