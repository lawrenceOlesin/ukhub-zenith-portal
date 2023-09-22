# Production

Below are the paths of our well-known endpoints for the production environment.

Our production authorisation server uses the strict profile defined above and testable in the Sandbox.

## Authorisation Server URLs
- OIDC Well Known endpoint: https://auth1.api.zenith.uk-hub-prod.ozoneapi.co.uk/.well-known/openid-configuration
- baseUrl: https://auth1.api.zenith.uk-hub-prod.ozoneapi.co.uk/
- Authorisation URL: https://api.zenith.uk-hub-prod.ozoneapi.co.uk/u/openbanking 

## Resource Server URLs
- Account Information Services API: https://rs1.api.zenith.uk-hub-prod.ozoneapi.co.uk/open-banking/v3.1/aisp/**

## Test accounts
If you require test accounts please contact mailto: Customer.Services@zenith-bank.co.uk

## Fall back channel
Zenith Bank’s MCI acts as a fall back channel in the event that open banking api’s are unavailable. The MCI enables a Third Party Provider (TPP) to access any of Zenith Bank’s Payment Service User (PSU) payment accounts via a browser based access channel.

Under PSR2017 regulation, Zenith Bank’s MCI requires a Qualified Web Authentication Certificate (QWAC) which will be validated by Zenith Bank as part of the connection establishment process.Upon successful connection and validation of the certificate, a TPP will then be required to get the PSU to authenticate (using their online banking credentials) in order to gain access to requested services.

## Production MCI endpoint
Zenith Bank’s endpoint where a TPP can get authorised MCI access is at
- https://zenith.mci.uk-hub-prod.ozoneapi.co.uk *

_*This endpoint is only available to TPPs with a valid QWAC._
