---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Create Metadata on File
  description: Used to create the metadata template instance for a corresponding Box
    file. When creating metadata, only values that adhere to the metadata template
    schema will be accepted.
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metadata_templates/schema:
    post:
      summary: Create Metadata Template
      description: Used to create a new metadata template with the specified schema.
      operationId: createMetadataTemplate
      x-api-path-slug: metadata-templatesschema-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Metadata
      - Templates
      - Schema
  /metadata_templates/{SCOPE}:
    get:
      summary: Get Enterprise Metadata
      description: Used to retrieve all metadata templates within a user's enterprise.
        Currently only the enterprise scope is supported.
      operationId: getEnterpriseMetadataTemplates
      x-api-path-slug: metadata-templatesscope-get
      parameters:
      - in: path
        name: SCOPE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Metadata
      - Templates
      - Scope
  /metadata_templates/{SCOPE}/{TEMPLATE}/schema:
    get:
      summary: Get Metadata Template
      description: Used to retrieve the schema for a given metadata template.
      operationId: getMetadataTemplate
      x-api-path-slug: metadata-templatesscopetemplateschema-get
      parameters:
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Metadata
      - Templates
      - Scope
      - Template
      - Schema
    put:
      summary: Update Metadata Template
      description: Used to update the schema of an existing template.
      operationId: updateMetadataTemplate
      x-api-path-slug: metadata-templatesscopetemplateschema-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Metadata
      - Templates
      - Scope
      - Template
      - Schema
  /files/{FILE_ID}/metadata:
    get:
      summary: Get all Metadata on File
      description: Used to retrieve all metadata associated with a given file
      operationId: getAllFileMetadata
      x-api-path-slug: filesfile-idmetadata-get
      parameters:
      - in: path
        name: FILE_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Files
      - File
      - ""
      - Metadata
  /files/{FILE_ID}/metadata/{SCOPE}/{TEMPLATE}:
    post:
      summary: Create Metadata on File
      description: Used to create the metadata template instance for a corresponding
        Box file. When creating metadata, only values that adhere to the metadata
        template schema will be accepted.
      operationId: createFileMetadata
      x-api-path-slug: filesfile-idmetadatascopetemplate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FILE_ID
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Files
      - File
      - ""
      - Metadata
      - Scope
      - Template
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