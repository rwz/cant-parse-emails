# Template For Contacting Web Services Support

Hi,

In using your Web service, I have noticed it is not possible 
to use a `name+string` pattern for email addresses. Would you 
be able to fix it? See details below:

## name+string email pattern

`name+string@example.org` is a valid email form. For example, 
the same user joe could have the following emails reaching the 
_same mailbox_:

* `joe@example.org`
* `joe+foo@example.org`
* `joe+bar@example.org`

You may want to check the [rfc5322] for the formal definition 
of the email syntax.
[rfc5322]: https://tools.ietf.org/html/rfc5322#section-3.4.1

## Why is it important?

* The pattern "name+string" is useful for filtering emails from 
    different services in mail clients or on mail servers (procmail 
    for example).
* It becomes easier to block the specific address if the address 
    is being used for another purpose than its original intended 
    purpose.

## Reading suggestions

* Good and detailed discussion on StackOverflow:
  http://stackoverflow.com/questions/201323/using-a-regular-expression-to-validate-an-email-address

* Practical article for PHP programmers:
  http://www.linuxjournal.com/article/9585

* An analysis of the idea of email validation:
  http://blog.sinjakli.co.uk/2011/02/13/email-address-validation-please-stop/

* Interesting comments:
  http://thedailywtf.com/articles/comments/Validating_Email_Addresses

Best Regards
