---
swagger: "2.0"
x-collection-name: Knoema
x-complete: 0
info:
  title: Knoema API Get timeseries list
  description: For the given dataset, this endpoint returns time series list for all
    the available frequencies with the combination of all the dimension members.
  version: 1.0.0
host: knoema.com
basePath: /api/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /meta/dataset:
    get:
      summary: List of datasets
      description: Returns the list of datasets
      operationId: listOfDatasets
      x-api-path-slug: metadataset-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /meta/dataset/{dataset id}:
    get:
      summary: Dataset details
      description: Lists out details of a particular dataset.
      operationId: datasetDetails
      x-api-path-slug: metadatasetdataset-id-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /meta/dataset/{datasetId}/dimension/{dimensionId}:
    get:
      summary: Dimension
      description: Lists out the given dataset's dimension details.
      operationId: datasetDimensions
      x-api-path-slug: metadatasetdatasetiddimensiondimensionid-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
      - Dimensions
  /data/dataset/{dataset id}:
    get:
      summary: Get timeseries list
      description: For the given dataset, this endpoint returns time series list for
        all the available frequencies with the combination of all the dimension members.
      operationId: getTimeseriesList
      x-api-path-slug: datadatasetdataset-id-get
      parameters:
      - in: path
        name: dataset id
        description: Unique dataset identifier
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Datasets
      - Time Series
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