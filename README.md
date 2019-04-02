# Mail template Gent Base

This mail template is used for system emails sent from websites or apps of the City of Ghent.

## When to use this mail template

Use the mail template for system emails.

System emails are emails that are **automatically sent from a system** to a user. The emails are linked with an action that the user has taken on a website or an app. These emails are functional emails that correspond with a specific functionality of the website or the app.

Examples of system emails:

* Newsletter subscription confirmation email
* Email address verification and confirmation email
* Email with password reset instructions (after the user filled in the "Forgot uyour password" form)

System mails are a part of a website or an app. The template should thus be in the same look and feel as the website or the app so that the user experience is consistent and uniform. The style and structure of system mails is also always similar.

## When not to use this mail template

Do not use the mail template for other mails than system emails.

Examples of mails that are **not** system emails:

* Newsletter emails
* Promotional emails
* Emails that are sent manually by a person using an email client

These kind of emails need another, specific template corresponding with the goal and the subject of the emails.

## How it works

To use the mail template in the system that sends the emails, the **CSS inside the mail template should be placed inline** instead of in the `<head>` tag.

This can be done by online tools such as <a href="https://htmlemail.io/inline/">Responsive Email CSS Inliner</a>.