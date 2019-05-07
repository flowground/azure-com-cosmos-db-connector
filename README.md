# ![LOGO](logo.png) Cosmos DB **flow**ground Connector

## Description

A generated **flow**ground connector for the Cosmos DB API (version 2015-04-08).

Generated from: https://api.apis.guru/v2/specs/azure.com/cosmos-db/2015-04-08/swagger.json<br/>
Generated at: 2019-05-07T17:37:54+03:00

## API Description

Azure Cosmos DB Database Service Resource Provider REST API

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Checks that the Azure Cosmos DB account name already exists. A valid account name may contain only lowercase letters, numbers, and the '-' character, and must be between 3 and 50 characters.

#### Input Parameters
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Lists all of the available Cosmos DB Resource Provider operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Lists all the Azure Cosmos DB database accounts available under the subscription.

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `subscriptionId` - _required_ - Azure subscription ID.

### Lists all the Azure Cosmos DB database accounts available under the given resource group.

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `subscriptionId` - _required_ - Azure subscription ID.

### Deletes an existing Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the properties of an existing Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Patches the properties of an existing Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Creates or updates an Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves metric definitions for the given collection.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the metrics determined by the given filter for the given database account and collection.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given partition key range id.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `partitionKeyRangeId` - _required_ - Partition Key Range Id for which to get data.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given collection, split by partition.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the usages (most recent storage data) for the given collection, split by partition.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _optional_ - An OData filter expression that describes a subset of usages to return. The supported parameter is name.value (name of the metric, can have an or of multiple names).

### Retrieves the usages (most recent storage data) for the given collection.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _optional_ - An OData filter expression that describes a subset of usages to return. The supported parameter is name.value (name of the metric, can have an or of multiple names).

### Retrieves metric definitions for the given database.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the metrics determined by the given filter for the given database account and database.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the usages (most recent data) for the given database.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _optional_ - An OData filter expression that describes a subset of usages to return. The supported parameter is name.value (name of the metric, can have an or of multiple names).

### Changes the failover priority for the Azure Cosmos DB database account. A failover priority of 0 indicates a write region. The maximum value for a failover priority = (total number of regions - 1). Failover priority values must be unique for each of the regions in which the database account exists.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Lists the connection strings for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Lists the access keys for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves metric definitions for the given database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the metrics determined by the given filter for the given database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Offline the specified region for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Online the specified region for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the metrics determined by the given filter for the given database account. This url is only for PBS and Replication Latency data

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Lists the read-only access keys for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Lists the read-only access keys for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Regenerates an access key for the specified Azure Cosmos DB database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.

### Retrieves the metrics determined by the given filter for the given database account, collection and region.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `region` - _required_ - Cosmos DB region, with spaces between words and each word capitalized.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given partition key range id and region.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `region` - _required_ - Cosmos DB region, with spaces between words and each word capitalized.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `partitionKeyRangeId` - _required_ - Partition Key Range Id for which to get data.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given collection and region, split by partition.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `region` - _required_ - Cosmos DB region, with spaces between words and each word capitalized.
* `databaseRid` - _required_ - Cosmos DB database rid.
* `collectionRid` - _required_ - Cosmos DB collection rid.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given database account and region.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `region` - _required_ - Cosmos DB region, with spaces between words and each word capitalized.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given account, source and target region. This url is only for PBS and Replication Latency data

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `sourceRegion` - _required_ - Source region from which data is written. Cosmos DB region, with spaces between words and each word capitalized.
* `targetRegion` - _required_ - Target region to which data is written. Cosmos DB region, with spaces between words and each word capitalized.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the metrics determined by the given filter for the given account target region. This url is only for PBS and Replication Latency data

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `targetRegion` - _required_ - Target region to which data is written. Cosmos DB region, with spaces between words and each word capitalized.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _required_ - An OData filter expression that describes a subset of metrics to return. The parameters that can be filtered are name.value (name of the metric, can have an or of multiple names), startTime, endTime, and timeGrain. The supported operator is eq.

### Retrieves the usages (most recent data) for the given database account.

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `accountName` - _required_ - Cosmos DB database account name.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-04-08.
* `$filter` - _optional_ - An OData filter expression that describes a subset of usages to return. The supported parameter is name.value (name of the metric, can have an or of multiple names).

## License

**flow**ground :- Telekom iPaaS / azure-com-cosmos-db-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
