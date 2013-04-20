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

    You may want to check the [rfc5321] for the formal definition 
    of the email syntax.
    [rfc5321]: http://tools.ietf.org/html/rfc5321#section-4.1.2

    ## Why is it important?

    * The pattern "name+string" is useful for filtering emails from 
      different services in mail clients or on mail servers (procmail 
      for example).
    * It becomes easier to block the specific address if the address 
      is being used for another purpose than its original intended 
      purpose.

    Best Regards
