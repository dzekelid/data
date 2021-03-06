---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Interbanks Get BAIBOR
  description: Returns a BAIBOR as of a date
  version: 1.0.0
host: www.xignite.com
basePath: xInterBanks.json/XigniteInterBanks
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListRates:
    get:
      summary: List Rates
      description: List supported interest rates.
      operationId: postListrates
      x-api-path-slug: listrates-get
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
      - Rates
  /SearchRates:
    get:
      summary: Search Rates
      description: Search rate names and description
      operationId: postSearchrates
      x-api-path-slug: searchrates-get
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
      - Search
      - Rates
  /GetLIBORSecure:
    get:
      summary: Get LIBOR Secure
      description: Returns Libor as of a date
      operationId: postGetliborsecure
      x-api-path-slug: getliborsecure-get
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
      - LIBOR
      - Secure
  /GetLIBOR:
    get:
      summary: Get LIBOR
      description: Returns Libor as of a date
      operationId: postGetlibor
      x-api-path-slug: getlibor-get
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
      - LIBOR
  /GetREIBOR:
    get:
      summary: Get REIBOR
      description: Returns a REIBOR as of a date
      operationId: postGetreibor
      x-api-path-slug: getreibor-get
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
      - REIBOR
  /GetHIBOR:
    get:
      summary: Get H I BOR
      description: Returns a HIBOR as of a date
      operationId: postGethibor
      x-api-path-slug: gethibor-get
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
      - H
      - I
      - BOR
  /GetBUBOR:
    get:
      summary: Get BUBOR
      description: Returns a BUBOR as of a date
      operationId: postGetbubor
      x-api-path-slug: getbubor-get
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
      - BUBOR
  /GetSOFIBOR:
    get:
      summary: Get SOFIBOR
      description: Returns a SOFIBOR as of a date
      operationId: postGetsofibor
      x-api-path-slug: getsofibor-get
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
      - SOFIBOR
  /GetREIBID:
    get:
      summary: Get REIBID
      description: Returns a REIBID as of a date
      operationId: postGetreib
      x-api-path-slug: getreibid-get
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
      - REIBID
  /GetOIBOR:
    get:
      summary: Get OIBOR
      description: Returns a OIBOR as of a date
      operationId: postGetoibor
      x-api-path-slug: getoibor-get
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
      - OIBOR
  /GetSIBOR:
    get:
      summary: Get SIBOR
      description: Returns a SIBOR as of a date
      operationId: postGetsibor
      x-api-path-slug: getsibor-get
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
      - SIBOR
  /GetCIBOR:
    get:
      summary: Get CIBOR
      description: Returns a CIBOR as of a date
      operationId: postGetcibor
      x-api-path-slug: getcibor-get
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
      - CIBOR
  /GetSTIBOR:
    get:
      summary: Get STIBOR
      description: Returns a STIBOR as of a date
      operationId: postGetstibor
      x-api-path-slug: getstibor-get
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
      - STIBOR
  /GetWIBOR:
    get:
      summary: Get WIBOR
      description: Returns a WIBOR as of a date
      operationId: postGetwibor
      x-api-path-slug: getwibor-get
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
      - WIBOR
  /GetVILIBOR:
    get:
      summary: Get VILIBOR
      description: Returns a VILIBOR as of a date
      operationId: postGetvilibor
      x-api-path-slug: getvilibor-get
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
      - VILIBOR
  /GetEURIBOR:
    get:
      summary: Get EURIBOR
      description: Returns a EURIBOR as of a date
      operationId: postGeteuribor
      x-api-path-slug: geteuribor-get
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
      - EURIBOR
  /GetPRIBOR:
    get:
      summary: Get PRIBOR
      description: Returns a PRIBOR as of a date
      operationId: postGetpribor
      x-api-path-slug: getpribor-get
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
      - PRIBOR
  /GetKORIBOR:
    get:
      summary: Get KORIBOR
      description: Returns a KORIBOR as of a date
      operationId: postGetkoribor
      x-api-path-slug: getkoribor-get
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
      - KORIBOR
  /GetMIBOR:
    get:
      summary: Get MIBOR
      description: Returns a MIBOR as of a date
      operationId: postGetmibor
      x-api-path-slug: getmibor-get
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
      - MIBOR
  /GetMIBID:
    get:
      summary: Get MIBID
      description: Returns a MIBOID as of a date
      operationId: postGetmib
      x-api-path-slug: getmibid-get
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
      - MIBID
  /GetSABOR:
    get:
      summary: Get SABOR
      description: Returns a SABOR as of a date
      operationId: postGetsabor
      x-api-path-slug: getsabor-get
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
      - SABOR
  /GetTAIBOR:
    get:
      summary: Get TAIBOR
      description: Returns a TAIBOR as of a date
      operationId: postGettaibor
      x-api-path-slug: gettaibor-get
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
      - TAIBOR
  /GetTURKIBOR:
    get:
      summary: Get TURKIBOR
      description: Returns a TURKIBOR as of a date
      operationId: postGetturkibor
      x-api-path-slug: getturkibor-get
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
      - TURKIBOR
  /GetMEXIBOR:
    get:
      summary: Get MEXIBOR
      description: Returns a MEXIBOR as of a date
      operationId: postGetmexibor
      x-api-path-slug: getmexibor-get
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
      - MEXIBOR
  /GetTELBOR:
    get:
      summary: Get TELBOR
      description: Returns a TELBOR as of a date
      operationId: postGettelbor
      x-api-path-slug: gettelbor-get
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
      - TELBOR
  /GetCHILIBOR:
    get:
      summary: Get CHILIBOR
      description: Returns a TELBOR as of a date
      operationId: postGetchilibor
      x-api-path-slug: getchilibor-get
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
      - CHILIBOR
  /GetCHIBOR:
    get:
      summary: Get CHIBOR
      description: Returns a CHIBOR as of a date
      operationId: postGetchibor
      x-api-path-slug: getchibor-get
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
      - CHIBOR
  /GetCDOR:
    get:
      summary: Get CDOR
      description: Returns a CDOR as of a date
      operationId: postGetcdor
      x-api-path-slug: getcdor-get
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
      - CDOR
  /GetKAIBOR:
    get:
      summary: Get KAIBOR
      description: Returns a KAIBOR as of a date
      operationId: postGetkaibor
      x-api-path-slug: getkaibor-get
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
      - KAIBOR
  /GetKIBOR:
    get:
      summary: Get KIBOR
      description: Returns a KIBOR as of a date
      operationId: postGetkibor
      x-api-path-slug: getkibor-get
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
      - KIBOR
  /GetKIBID:
    get:
      summary: Get KIBID
      description: Returns a KIBID as of a date
      operationId: postGetkib
      x-api-path-slug: getkibid-get
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
      - KIBID
  /GetSHIBOR:
    get:
      summary: Get SHIBOR
      description: Returns a SHIBOR as of a date
      operationId: postGetshibor
      x-api-path-slug: getshibor-get
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
      - SHIBOR
  /GetJIBOR:
    get:
      summary: Get JIBOR
      description: Returns a JIBOR as of a date
      operationId: postGetjibor
      x-api-path-slug: getjibor-get
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
      - JIBOR
  /GetKLIBOR:
    get:
      summary: Get KLIBOR
      description: Returns a KLIBOR as of a date
      operationId: postGetklibor
      x-api-path-slug: getklibor-get
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
      - KLIBOR
  /GetTIBOR:
    get:
      summary: Get TIBOR
      description: Returns a TIBOR as of a date
      operationId: postGettibor
      x-api-path-slug: gettibor-get
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
      - TIBOR
  /GetPHIBOR:
    get:
      summary: Get PHIBOR
      description: Returns a PHIBOR as of a date
      operationId: postGetphibor
      x-api-path-slug: getphibor-get
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
      - PHIBOR
  /GetBKIBOR:
    get:
      summary: Get BKIBOR
      description: Returns a BKIBOR as of a date
      operationId: postGetbkibor
      x-api-path-slug: getbkibor-get
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
      - BKIBOR
  /GetVNIBOR:
    get:
      summary: Get VNIBOR
      description: Returns a VNIBOR as of a date
      operationId: postGetvnibor
      x-api-path-slug: getvnibor-get
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
      - VNIBOR
  /GetMOSIBOR:
    get:
      summary: Get MOSIBOR
      description: Returns a MOSIBOR as of a date
      operationId: postGetmosibor
      x-api-path-slug: getmosibor-get
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
      - MOSIBOR
  /GetMOSIBID:
    get:
      summary: Get MOSIBID
      description: Returns a MOSIBID as of a date
      operationId: postGetmosib
      x-api-path-slug: getmosibid-get
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
      - MOSIBID
  /GetHistoricalLIBOR:
    get:
      summary: Get Historical LIBOR
      description: ""
      operationId: postGethistoricallibor
      x-api-path-slug: gethistoricallibor-get
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
      - Historical
      - LIBOR
  /GetBRAZIBOR:
    get:
      summary: Get BRAZIBOR
      description: Returns a BRAZIBOR as of a date
      operationId: postGetbrazibor
      x-api-path-slug: getbrazibor-get
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
      - BRAZIBOR
  /GetTRLIBOR:
    get:
      summary: Get TRLIBOR
      description: Returns a TRLIBOR as of a date
      operationId: postGettrlibor
      x-api-path-slug: gettrlibor-get
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
      - TRLIBOR
  /GetTRLIBID:
    get:
      summary: Get TRLIBID
      description: Returns a TRLIBID as of a date
      operationId: postGettrlib
      x-api-path-slug: gettrlibid-get
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
      - TRLIBID
  /GetBRIBOR:
    get:
      summary: Get BRIBOR
      description: Returns a BRIBOR as of a date
      operationId: postGetbribor
      x-api-path-slug: getbribor-get
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
      - BRIBOR
  /GetBRIBID:
    get:
      summary: Get BRIBID
      description: Returns a BRIBID as of a date
      operationId: postGetbrib
      x-api-path-slug: getbribid-get
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
      - BRIBID
  /GetRIGIBOR:
    get:
      summary: Get RIGIBOR
      description: Returns a RIGIBOR as of a date
      operationId: postGetrigibor
      x-api-path-slug: getrigibor-get
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
      - RIGIBOR
  /GetRIGIBID:
    get:
      summary: Get RIGIBID
      description: Returns a RIGIBID as of a date
      operationId: postGetrigib
      x-api-path-slug: getrigibid-get
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
      - RIGIBID
  /GetAIDIBOR:
    get:
      summary: Get AIDIBOR
      description: Returns a AIDIBOR as of a date
      operationId: postGetaibor
      x-api-path-slug: getaidibor-get
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
      - AIDIBOR
  /GetJIBAR:
    get:
      summary: Get JIBAR
      description: Returns a JIBAR as of a date
      operationId: postGetjibar
      x-api-path-slug: getjibar-get
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
      - JIBAR
  /GetBAIBOR:
    get:
      summary: Get BAIBOR
      description: Returns a BAIBOR as of a date
      operationId: postGetbaibor
      x-api-path-slug: getbaibor-get
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
      - BAIBOR
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