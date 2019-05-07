# ![LOGO](logo.png) BackupManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the BackupManagementClient API (version 2018-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Backups/2018-09-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:25+03:00

## API Description

The Admin Backup Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of backups from a location.

*Tags:* `Backups`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Name of the backup location.
* `api-version` - _required_ - Client API version.

### Returns a backup from a location based on name.

*Tags:* `Backups`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Name of the backup location.
* `backup` - _required_ - Name of the backup.
* `api-version` - _required_ - Client API version.

### Restore a backup.

*Tags:* `Backups`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Name of the backup location.
* `resourceGroupName` - _required_ - Name of the resource group.
* `backup` - _required_ - Name of the backup.
* `api-version` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-backups-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
