# Paystation gateway postman collection

This is a postman collection of our [Paystation API](https://docs.paystation.co.nz)

## Requirements

You'll need to supply your own Paystation gateway credentials, if you don't have these please [contact us](https://www2.paystation.co.nz/contact-us)

Requires the installation of [Postman](https://www.getpostman.com/).

[Postman guide to environment management](https://learning.getpostman.com/docs/postman/environments_and_globals/manage_environments)

### Environment variables

- PaystationAccount - Test Paystation Account ID - (e.g 600000)
- PaystationGateway - Test Paystation Gateway ID - (e.g PAYSTATION)
- CardNumber - Test card - [List of test cards](https://www2.paystation.co.nz/developers/test-cards/)
- Expiry - Test expiry
- CSC - Test card security code
- DynamicUrl (optional) - Dynamic return url (e.g https://your-website-co.nz)
- HmacKey - Test HMAC key (only required for HMAC authenticated endpoints)

## Installing

1) Download `paystation.postman_collection` and `paystation.postman_environment`
2) Open Postman, click on Import in the top left and select the two json files.
3) Once imported, a new API collection will be created, along with the environment.
