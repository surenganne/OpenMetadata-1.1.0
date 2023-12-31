---
title: bigQueryConnection
slug: /main-concepts/metadata-standard/schemas/entity/services/connections/database/bigqueryconnection
---

# BigQueryConnection

*Google BigQuery Connection Config*

## Properties

- **`type`**: Service Type. Refer to *#/definitions/bigqueryType*. Default: `BigQuery`.
- **`scheme`**: SQLAlchemy driver scheme options. Refer to *#/definitions/bigqueryScheme*. Default: `bigquery`.
- **`hostPort`** *(string)*: BigQuery APIs URL. Default: `bigquery.googleapis.com`.
- **`credentials`**: GCP Credentials. Refer to *../../../../security/credentials/gcpCredentials.json*.
- **`tagCategoryName`** *(string)*: Custom OpenMetadata Tag category name for BigQuery policy tags. Default: `BigqueryPolicyTags`.
- **`taxonomyLocation`** *(string)*: Taxonomy location used to fetch policy tags. Default: `us`.
- **`usageLocation`** *(string)*: Location used to query INFORMATION_SCHEMA.JOBS_BY_PROJECT to fetch usage data. You can pass multi-regions, such as `us` or `eu`, or you specific region. Australia and Asia multi-regions are not yet in GA. Default: `us`.
- **`connectionOptions`**: Refer to *../connectionBasicType.json#/definitions/connectionOptions*.
- **`connectionArguments`**: Refer to *../connectionBasicType.json#/definitions/connectionArguments*.
- **`supportsMetadataExtraction`**: Refer to *../connectionBasicType.json#/definitions/supportsMetadataExtraction*.
- **`supportsUsageExtraction`**: Refer to *../connectionBasicType.json#/definitions/supportsUsageExtraction*.
- **`supportsProfiler`**: Refer to *../connectionBasicType.json#/definitions/supportsProfiler*.
## Definitions

- **`bigqueryType`** *(string)*: Service type. Must be one of: `['BigQuery']`. Default: `BigQuery`.
- **`bigqueryScheme`** *(string)*: SQLAlchemy driver scheme options. Must be one of: `['bigquery']`. Default: `bigquery`.


Documentation file automatically generated at 2022-07-14 10:51:34.749986.
