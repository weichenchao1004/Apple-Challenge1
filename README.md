# Apple-Challenge1
HTML5 Validation for Apple login test
The Sign up

Overview

Create a sign up page. This must be accessible and validate user data entered into all fields.

Requirements
1. Fields
Username

Username must be an email address. It cannot be longer than 56 characters. Required.

Password & Confirm Password

Must be at least 6 characters. Passwords must match. Required.

First & Last Name

Letters only. May not be more than 50 characters. Last Name Optional

Birthday

Must be visible to the user in MM/DD/YYYY (03/21/1982) format, but submit as ISO 8601. User must be at least 14 and not older than 150. Required.

1. Submit

Occurs either on button press or when the user hits the enter key.
Only submits when there are no errors.
Does not depend on the <form> element.
On success, takes the user to a success view.

1. Clear

Clear all entered user data and any errors on click.
Provide a confirmation dialog before clearing.


1. Success View

Should be same-page as the form. Treat this like a SPA.
Displays the user’s information.
Allow the user to expand their profile by adding a bio and interests.
