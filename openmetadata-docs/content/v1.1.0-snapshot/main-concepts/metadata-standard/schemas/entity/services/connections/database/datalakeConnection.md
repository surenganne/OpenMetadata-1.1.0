---
title: datalakeConnection
slug: /main-concepts/metadata-standard/schemas/entity/services/connections/database/datalakeconnection
---

# DatalakeConnection

*Datalake Connection Config*

## Properties

- **`type`**: Service Type. Refer to *#/definitions/datalakeType*. Default: `Datalake`.
- **`configSource`**: Available sources to fetch files.
- **`bucketName`** *(string)*: Bucket Name of the data source. Default: ``.
- **`prefix`** *(string)*: The prefix of a data source in datalake refers to the first part of the data path that identifies the source or origin of the data. It's used to organize and categorize data within the datalake, and can help users easily locate and access the data they need. Default: ``.
- **`connectionOptions`**: Refer to *../connectionBasicType.json#/definitions/connectionOptions*.
- **`connectionArguments`**: Refer to *../connectionBasicType.json#/definitions/connectionArguments*.
- **`supportsMetadataExtraction`**: Refer to *../connectionBasicType.json#/definitions/supportsMetadataExtraction*.
## Definitions

- **`datalakeType`** *(string)*: Service type. Must be one of: `['Datalake']`. Default: `Datalake`.
- **`GCSConfig`**: DataLake Catalog and Manifest files in GCS storage. We will search for catalog.json and manifest.json.
  - **`securityConfig`**: Refer to *../../../../security/credentials/gcpCredentials.json*.
- **`S3Config`**: DataLake Catalog and Manifest files in S3 bucket. We will search for catalog.json and manifest.json.
  - **`securityConfig`**: Refer to *../../../../security/credentials/awsCredentials.json*.


Documentation file automatically generated at 2022-07-14 10:51:34.749986.
