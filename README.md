# Mail Template Gent Base

This mail template is used for system emails sent from websites or apps of the City of Ghent. The mail template follows the corporate identity of the City of Ghent.

## When to use this mail template

**Use the mail template for system emails.**

System emails are emails that are **automatically sent from a system** to a user. The emails are linked with an action that the user has taken on a website or an app. These emails are functional emails that correspond with a specific functionality of the website or the app.

Examples of system emails:

* Newsletter subscription confirmation email
* Email address verification and confirmation email
* Email with password reset instructions (after the user filled in the password reset form of the website or the app)

System emails are part of a website or an app. Therefore, the template should  be in the same style and look and feel as the website or the app so that the user experience is consistent and uniform. The style and structure of system emails is also always similar.

## When not to use this mail template

**Do not use the mail template for other mails than system emails.**

Examples of mails that are **not** system emails:

* Newsletter emails
* Promotional emails
* Emails that are sent manually by a person using an email client

These kind of emails need another, specific template, style and look and feel corresponding with the goal and the subject of the emails.

## How it works

To use the mail template, the **CSS should be placed inline** instead of in the `<head>` tag.

This can be done by online tools such as <a href="https://htmlemail.io/inline/">Responsive Email CSS Inliner</a>.

The mail template shown is an example in its most minimal form. The mail template is in the dutch language.

The mail template has the following structure:

* City of Ghent logo (required and fixed)
* Website title (optional, title or name of the website or app where the system mails are sent from)
* Title (required, should be short and specific, should indicate the use case or action the user is taking)
* Introduction text (optional)
* Main content
* Contact information (optional but recommended, Gentinfo contact information or contact information of the reponsible City of Ghent city service)
* Email footer text (required and fixed)

## Examples

To show how the mail template could work in specific applications, the following examples can be found in the `/examples` folder:

* Email with login link to login to websites of the City of Ghent
* Email that a user gets when a request is submitted to be able to enter the low-emission zone of the City of Ghent

 The examples included are in the dutch language.