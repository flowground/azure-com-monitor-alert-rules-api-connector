# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2016-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-alertRules_API/2016-03-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:25+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List the alert rules within a subscription.

*Tags:* `AlertRules`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### List the alert rules within a resource group.

*Tags:* `AlertRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Deletes an alert rule

*Tags:* `AlertRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Gets an alert rule

*Tags:* `AlertRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Updates an existing AlertRuleResource. To update other fields use the CreateOrUpdate method.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Creates or updates an alert rule.

*Tags:* `AlertRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-alert-rules-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
