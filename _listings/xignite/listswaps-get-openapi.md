---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Futures List Swaps
  description: List all commodity swaps and the exchange on which they are traded.
  version: 1.0.0
host: www.xignite.com
basePath: xFutures.json/XigniteFutures
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetFutureSymbol:
    get:
      summary: Get Future Symbol
      description: Returns the symbol for a future based on its month and year.
      operationId: postGetfuturesymbol
      x-api-path-slug: getfuturesymbol-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Future
      - Symbol
  /GetReverseFutureSymbol:
    get:
      summary: Get Reverse Future Symbol
      description: Returns the symbol for a future based on its month and year.
      operationId: postGetreversefuturesymbol
      x-api-path-slug: getreversefuturesymbol-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Reverse
      - Future
      - Symbol
  /GetTerminationSchedule:
    get:
      summary: Get Termination Schedule
      description: Provide a termination schedule for a commodity.
      operationId: postGetterminationschedule
      x-api-path-slug: getterminationschedule-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Termination
      - Schedule
  /GetNextFuture:
    get:
      summary: Get Next Future
      description: Get the next immediate future contract for a commodity.
      operationId: postGetnextfuture
      x-api-path-slug: getnextfuture-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Next
      - Future
  /GetFuture:
    get:
      summary: Get Future
      description: Provide information about a commodity future.
      operationId: postGetfuture
      x-api-path-slug: getfuture-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Future
  /ListExchanges:
    get:
      summary: List Exchanges
      description: List commmodities future exchanges and indicates which ones are
        supported.
      operationId: postListexchanges
      x-api-path-slug: listexchanges-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Exchanges
  /ListFutureCategories:
    get:
      summary: List Future Categories
      description: List commmodities future categories.
      operationId: postListfuturecategories
      x-api-path-slug: listfuturecategories-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Future
      - Categories
  /ListSwaps:
    get:
      summary: List Swaps
      description: List all commodity swaps and the exchange on which they are traded.
      operationId: postListswaps
      x-api-path-slug: listswaps-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Swaps
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