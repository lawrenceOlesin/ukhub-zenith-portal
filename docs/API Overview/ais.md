# AISP API Overview

## Base URL
The base URL for all AIS APIs is: `https://rs1.api.zenith.uk-hub-prod.ozoneapi.co.uk/open-banking/v3.1/aisp/**`

## Account Access Consents
[Account Access Consents API](/perry/developer/documentation?resource=ukhub-zenith-portal&document=swagger/account-info-openapi.yaml#operations-tag-Account_Access)

## Accounts
[Accounts API](/perry/developer/documentation?resource=ukhub-zenith-portal&document=swagger/account-info-openapi.yaml#operations-tag-Accounts)

Zenith members will have one or more of the following accounts:
- Zenith Personal Account
- Zenith Personal Savings Pot
- Zenith Joint Account
- Zenith Joint Savings Pot
- Zenith Business Current Account
- Zenith Business Savings Pot

## Balances
[Balances API](/perry/developer/documentation?resource=ukhub-zenith-portal&document=swagger/account-info-openapi.yaml#operations-tag-Balances)

Balances shown in this endpoint provide the `InterimAvailable` value.

`InterimAvailable` balance is the value displayed most widely to our members within the Zenith apps.

## Transactions
[Transactions API](/perry/developer/documentation?resource=ukhub-cot-portal&document=swagger/account-info-openapi.yaml#operations-tag-Transactions)

Pagination is supported on GET /accounts/{AccountId}/transactions end point with a page size of 100 transactions.

Please note:  
- GET /transactions end point is not supported  
- Currently we only provide 7-day transactions, but we are finalizing transactions for longer periods  

