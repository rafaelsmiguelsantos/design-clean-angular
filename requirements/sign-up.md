## Requirements to register customer

The customer can register on the platform at any time. Information that is necessary to create a valid registration:

- FirstName
- Email ID
- Password
- Confirm Password
- Phone Number

Required fields are:

- Email ID
- Password
- Confirm Password
- Phone Number

## Validations

Validation for fields:

- First Name: Should only allow letters in your field. Field length must be between 8 to 15 characters. Must not allow special characters.

- Email: The customer must have a valid email. The email cannot contain more than 200 characters.

- Password: It should have alphanumeric, Length should be 8 to 32 and must contain at least one special character.

- PhoneNumber: should have only Numbers, Country code is required. Must contain mask for phone and have a maximum of 12 characters.

## Success Customer Register ✅

At the end of the registration process, in case of success, a message should be displayed informing the user that their account has been created. In sequence it should be redirected to the main system page.

Content of the message to be displayed:

- Registration successfully completed! You are being redirected to the page center!

## Error Customer Register ❌

The customer must be informed when filling out the registration if he is not meeting any requirement of the mandatory fields on the screen.

If the password or password is incorrect the backend response will always be, 'Invalid password or email'