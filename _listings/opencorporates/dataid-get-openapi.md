---
swagger: "2.0"
x-collection-name: OpenCorporates
x-complete: 0
info:
  title: OpenCorporates Data  ID
  description: nThis returns information on a given datum
  termsOfService: https://opencorporates.com/info/licence
  version: v.04
host: api.opencorporates.com
basePath: v0.4/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies/:jurisdiction_code/:company_number/data:
    get:
      summary: Companies  Jurisdiction Code  Company Number Data
      description: nThis returns the data held for the given company
      operationId: companies--jurisdiction-code--company-number-data
      x-api-path-slug: companiesjurisdiction-codecompany-numberdata-get
      parameters:
      - in: query
        name: data_type
        description: this is a string value denoting the type of data, e
      - in: query
        name: description
        description: the given description of the datum as displayed on OpenCorporates
      - in: query
        name: id
        description: the id given to the filing by the company registry
      - in: query
        name: title
        description: this is the title of the datum as displayed on OpenCorporates
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Companies
      - :jurisdiction
      - Code
      - :company
      - Number
      - Data
  /data/:id:
    get:
      summary: Data  ID
      description: nThis returns information on a given datum
      operationId: data--id
      x-api-path-slug: dataid-get
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Data
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