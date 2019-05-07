# ![LOGO](logo.png) SearchServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SearchServiceClient API (version 2017-11-11-Preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/search-searchservice/2017-11-11-Preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:49+03:00

## API Description

Client that can be used to manage and query indexes and documents, as well as manage other resources, on an Azure Search service.

## Authorization

This API does not require authorization.

## Actions

### Lists all datasources available for an Azure Search service.

*Tags:* `DataSources`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search datasource.

*Tags:* `DataSources`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Deletes an Azure Search datasource.

*Tags:* `DataSources`

#### Input Parameters
* `dataSourceName` - _required_ - The name of the datasource to delete.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `api-version` - _required_ - Client Api Version.

### Retrieves a datasource definition from Azure Search.

*Tags:* `DataSources`

#### Input Parameters
* `dataSourceName` - _required_ - The name of the datasource to retrieve.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search datasource or updates a datasource if it already exists.

*Tags:* `DataSources`

#### Input Parameters
* `dataSourceName` - _required_ - The name of the datasource to create or update.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `Prefer` - _required_ - For HTTP PUT requests, instructs the service to return the created/updated resource on success.
    Possible values: return=representation.
* `api-version` - _required_ - Client Api Version.

### Lists all indexers available for an Azure Search service.

*Tags:* `Indexers`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search indexer.

*Tags:* `Indexers`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Deletes an Azure Search indexer.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer to delete.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `api-version` - _required_ - Client Api Version.

### Retrieves an indexer definition from Azure Search.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer to retrieve.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search indexer or updates an indexer if it already exists.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer to create or update.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `Prefer` - _required_ - For HTTP PUT requests, instructs the service to return the created/updated resource on success.
    Possible values: return=representation.
* `api-version` - _required_ - Client Api Version.

### Resets the change tracking state associated with an Azure Search indexer.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer to reset.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Runs an Azure Search indexer on-demand.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer to run.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Returns the current status and execution history of an indexer.

*Tags:* `Indexers`

#### Input Parameters
* `indexerName` - _required_ - The name of the indexer for which to retrieve status.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Lists all indexes available for an Azure Search service.

*Tags:* `Indexes`

#### Input Parameters
* `$select` - _optional_ - Selects which properties of the index definitions to retrieve. Specified as a comma-separated list of JSON property names, or '*' for all properties. The default is all properties.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search index.

*Tags:* `Indexes`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Deletes an Azure Search index and all the documents it contains.

*Tags:* `Indexes`

#### Input Parameters
* `indexName` - _required_ - The name of the index to delete.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `api-version` - _required_ - Client Api Version.

### Retrieves an index definition from Azure Search.

*Tags:* `Indexes`

#### Input Parameters
* `indexName` - _required_ - The name of the index to retrieve.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search index or updates an index if it already exists.

*Tags:* `Indexes`

#### Input Parameters
* `indexName` - _required_ - The definition of the index to create or update.
* `allowIndexDowntime` - _optional_ - Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds. This temporarily causes indexing and query requests to fail. Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `Prefer` - _required_ - For HTTP PUT requests, instructs the service to return the created/updated resource on success.
    Possible values: return=representation.
* `api-version` - _required_ - Client Api Version.

### Shows how an analyzer breaks text into tokens.

*Tags:* `Indexes`

#### Input Parameters
* `indexName` - _required_ - The name of the index for which to test an analyzer.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Returns statistics for the given index, including a document count and storage usage.

*Tags:* `Indexes`

#### Input Parameters
* `indexName` - _required_ - The name of the index for which to retrieve statistics.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Gets service level statistics for an Azure Search service.

*Tags:* `Service`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### List all cognitive skillsets in an Azure Search service.

*Tags:* `Skillsets`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new cognitive skillset in an Azure Search service.

*Tags:* `Skillsets`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Deletes a cognitive skillset in an Azure Search service.

*Tags:* `Skillsets`

#### Input Parameters
* `skillsetName` - _required_ - The name of the skillset to delete.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Retrieves a cognitive skillset in an Azure Search service.

*Tags:* `Skillsets`

#### Input Parameters
* `skillsetName` - _required_ - The name of the skillset to retrieve.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new cognitive skillset in an Azure Search service or updates the skillset if it already exists.

*Tags:* `Skillsets`

#### Input Parameters
* `skillsetName` - _required_ - The name of the skillset to create or update.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `Prefer` - _required_ - For HTTP PUT requests, instructs the service to return the created/updated resource on success.
    Possible values: return=representation.
* `api-version` - _required_ - Client Api Version.

### Lists all synonym maps available for an Azure Search service.

*Tags:* `SynonymMaps`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search synonym map.

*Tags:* `SynonymMaps`

#### Input Parameters
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Deletes an Azure Search synonym map.

*Tags:* `SynonymMaps`

#### Input Parameters
* `synonymMapName` - _required_ - The name of the synonym map to delete.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `api-version` - _required_ - Client Api Version.

### Retrieves a synonym map definition from Azure Search.

*Tags:* `SynonymMaps`

#### Input Parameters
* `synonymMapName` - _required_ - The name of the synonym map to retrieve.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `api-version` - _required_ - Client Api Version.

### Creates a new Azure Search synonym map or updates a synonym map if it already exists.

*Tags:* `SynonymMaps`

#### Input Parameters
* `synonymMapName` - _required_ - The name of the synonym map to create or update.
* `client-request-id` - _optional_ - The tracking ID sent with the request to help with debugging.
* `If-Match` - _optional_ - Defines the If-Match condition. The operation will be performed only if the ETag on the server matches this value.
* `If-None-Match` - _optional_ - Defines the If-None-Match condition. The operation will be performed only if the ETag on the server does not match this value.
* `Prefer` - _required_ - For HTTP PUT requests, instructs the service to return the created/updated resource on success.
    Possible values: return=representation.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-search-searchservice-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
