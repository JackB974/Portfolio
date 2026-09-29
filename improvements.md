# Improvements

## Add a "Me contacter" section

Add a contact section to both pages ("Me contacter" in French, "Contact me" in English). Visitors can write a message that is sent to my email account, but the email address must never appear on the site or in its source code.

Notes:
- The site is static on GitHub Pages, so it cannot send email by itself. A form service such as Formspree or Web3Forms receives the message and forwards it to my inbox. The page only contains the service's form endpoint or public key, never the address.
- Fields: name, email address to reply to, message. Add spam protection (a honeypot field or the service's captcha).
- Show a confirmation message after sending, and an error message if sending fails.
- Add a "Me contacter" / "Contact me" link to the sidebar menu.
- Update the README: it currently says the site has no email address, which stays true.
