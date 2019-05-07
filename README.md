# ![LOGO](logo.png) CompanyAPI **flow**ground Connector

## Description

A generated **flow**ground connector for the CompanyAPI API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/roaring.io/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:55+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### get_company_board_members

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyId` - _required_ - Company identification for the company

### post_company_board_members

#### Input Parameters
* `countryCode` - _required_ - Country code for the company

### get_company_credit_decision

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyId` - _required_ - Company identification for the company
* `template` - _required_ - Template for credit decision

### get_company_economy_overview

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyId` - _required_ - Company identification for the company

### post_company_economy_overview

#### Input Parameters
* `countryCode` - _required_ - Country code for the company

### post_company_event

#### Input Parameters
* `countryCode` - _required_ - Country code for the company

### get_company_overview

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyId` - _required_ - Company identification for the company

### post_company_overview

#### Input Parameters
* `countryCode` - _required_ - Country code for the company

### get_company_signatory

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyId` - _required_ - Company identification for the company

### post_company_signatory

#### Input Parameters
* `countryCode` - _required_ - Country code for the company

### get_company_simple_search

#### Input Parameters
* `countryCode` - _required_ - Country code for the company
* `companyName` - _optional_ - Company name
* `town` - _optional_ - Town

## License

**flow**ground :- Telekom iPaaS / roaring-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
