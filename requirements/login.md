## Requirements Login Page

The customer, if he has an account, can log in at any time. For this page you will be asked to enter information in two fields, email ID and password.

## Required Fields

- Email ID
- Password

## Validations

If both fields are not filled in, the button must remain disabled, preventing the client from sending requests.

- Email: Required Field. The customer must have a valid email. The email cannot contain more than 200 characters.
- Password: Required Field. Just check if field is filled.

## Success Customer Register ✅

If the data is filled in and correct in the request, the backend should return a success response with status 200.

## Error Customer Register ❌

If the data sent in the request is invalid, the backend will respond with a 401. In this case, the application should display a toastr warning that the request failed because the data sent is not correct. Fields must not be reset.
