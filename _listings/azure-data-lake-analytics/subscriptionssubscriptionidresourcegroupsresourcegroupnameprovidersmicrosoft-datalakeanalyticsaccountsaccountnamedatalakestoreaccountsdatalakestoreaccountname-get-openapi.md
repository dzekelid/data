---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Data Lake Store Accounts Get
  description: Gets the specified Data Lake Store account details in the specified
    Data Lake Analytics account.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  : get:
      summary: Data Lake Store Accounts Get
      description: Gets the specified Data Lake Store account details in the specified
        Data Lake Analytics account.
      operationId: DataLakeStoreAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          the Data Lake Store account details
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---