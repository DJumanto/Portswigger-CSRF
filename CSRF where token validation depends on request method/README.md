# CSRF where token validation depends on request method

In this challenge we have to perform an csrf attack, where we had to chang a user email without their consent. A few anlysis we had to do:

- What payload do we need to perform email-change?
- Do we need csrf token to perform email-change?
- Do we able to change email using different request method?

To Check all of those, we can use burp repeater.
