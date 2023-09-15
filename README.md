
# Open API for Banking to manage account services

This project desing OpenAPI sepcification in (OAS 3.0.x) platform. To transformatin customer journey to digitalize into self service for Open Banking has captured the imagination of digital leaders and is emopowering customers to use new digital services with their banking information. Harnessing the power of platform that is open source, is helping banks to be in control of their own destintity and accelerating innovation. Create an ecosystem, connect with your customers or simply make it easier to partner with you. The objective of this project is to provide a an accelerator for open banking


## API

#### /api/v1/customer/{custID}/accounts
* `GET` : Get all accounts details

####  /api/v1/accounts/{accountNumber}
* `GET` : Get both current and saving account details
* `POST`: Create new account number
* `PUT` : Update account details
* `DELETE` : Delete account number

#### /api/v1/accounts/{accountNumber}/transactions
* `GET` : reterive transaction history for specific account

####  /api/v1/accounts/{accountNumber}/transfers
* `POST` : Fund transfer to beneficiary account 


## Structure
```
├── assignmentroot.yaml
│   ├── schemas
│   │   └── requestsechemas
│  │   │   └── AccountTransferRequest.yaml     // APIs for Task model
│  │   │   └── AccountTransferAccountRequest.yaml     // APIs for Task model
│  │   │   └── SavingAccountTypeResponse.yaml
│  │   │   └── SavingAccountTypeResponse.yaml
│  │   │   └── SavingAccountTypeResponse.yaml
│  │   │   └── SavingAccountTypeResponse.yaml
│  │   │   └── SavingAccountTypeResponse.yaml 
│  │   │   └── SavingAccountTypeResponse.yaml 
│   │   └── responsechemas
│  │   │   └── AccountTypeResponse.yaml     // APIs for Task model
│  │   │   └── AccountCardResponse.yaml     // APIs for Task model
│  │   │   └── CreateNewAccountRequest.yaml
│  │   │   └── UpdateAccountRequest.yaml
│  │   └── commonschemas
│  │   │   └── ProblemDetails.yaml
│  │   │   └── ValidationProblemDetails.yaml
│  │   │   └── ProblemDetails.yaml
│  │   │   └── SecuritySchemas.yaml
│  ├── examples
│   │   └── 200.yaml
│   │   └── 201.yaml
│   │   └── 204.yaml
│   │   └── 400.yaml
│   │   └── 401.yaml
│   │   └── 402.yaml
│   │   └── 404.yaml
│   │   └── 500.yaml


## Todo

- [x] Support  REST APIs all standars and patterns.
- [x] Support OpenAPI(OAS 3.0.x) all standards.
- [x] Support platform 360 degree view for all business LOBs.
- [x] Support authentication and autherization.
- [x] Add all mock examples  to support all test coverage for successful response, request and error scenarios
- [x] follow all organization standars and complinaces
- [x] Cover all business scenarios   

## Install


## Run the app


## Run the tests


## Contributing
Github URL:

## License

Copyright 2018-2020 XXX, Inc.
