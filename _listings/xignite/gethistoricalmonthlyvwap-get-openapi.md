---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite VWAP Get Historical Monthly VWAP
  description: Returns historical monthly VWAP information for a date range.
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetEventsForMonth:
    get:
      summary: Get Events For Month
      description: Get events for the specified date.
      operationId: postGeteventsformonth
      x-api-path-slug: geteventsformonth-get
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
      - Events
      - Month
  /GetHistoricalMonthlyCrossRatesRange:
    get:
      summary: Get Historical Monthly Cross Rates Range
      description: This operation returns a complete range of stock quotes for a currency
        pair.
      operationId: postGethistoricalmonthlycrossratesrange
      x-api-path-slug: gethistoricalmonthlycrossratesrange-get
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
      - Monthly
      - Cross
      - Rates
      - Range
  /GetHistoricalCommodityMonthlyRange:
    get:
      summary: Get Historical Commodity Monthly Range
      description: Returns a range of historical quotes for a future contract.
      operationId: postGethistoricalcommoditymonthlyrange
      x-api-path-slug: gethistoricalcommoditymonthlyrange-get
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
      - Commodity
      - Monthly
      - Range
  /GetHistoricalSpotMonthlyRange:
    get:
      summary: Get Historical Spot Monthly Range
      description: Returns a range of commodity spot prices for a commodity.
      operationId: postGethistoricalspotmonthlyrange
      x-api-path-slug: gethistoricalspotmonthlyrange-get
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
      - Spot
      - Monthly
      - Range
  /ListFrontMonthContracts:
    get:
      summary: List Front Month Contracts
      description: List all commodity future Front Month Contracts.
      operationId: postListfrontmonthcontracts
      x-api-path-slug: listfrontmonthcontracts-get
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
      - Front
      - Month
      - Contracts
  /GetFrontMonthFuture:
    get:
      summary: Get Front Month Future
      description: Returns master data on the front month future contract
      operationId: GetFrontMonthFuture
      x-api-path-slug: getfrontmonthfuture-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Front
      - Month
      - Future
  /GetLatestFrontMonthFutureQuotes:
    get:
      summary: Get Latest Front Month Future Quotes
      description: Returns latest quotes for front month futures
      operationId: GetLatestFrontMonthFutureQuotes
      x-api-path-slug: getlatestfrontmonthfuturequotes-get
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
      - Latest
      - Front
      - Month
      - Future
      - Quotes
  /GetGlobalHistoricalMonthlyQuotesRange:
    get:
      summary: Get Global Historical Monthly Quotes Range
      description: This operation returns a range of monthly quotes for an equity
        based on the specified date range. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalmonthlyquotesrange
      x-api-path-slug: getglobalhistoricalmonthlyquotesrange-get
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
      - Global
      - Historical
      - Monthly
      - Quotes
      - Range
  /GetGlobalHistoricalMonthlyQuotesRangeExtended:
    get:
      summary: Get Global Historical Monthly Quotes Range Extended
      description: This operation returns a range of monthly quotes extended for an
        equity based on the specified date range. This includes the adjusted price
        as specified.
      operationId: postGetglobalhistoricalmonthlyquotesrangeextended
      x-api-path-slug: getglobalhistoricalmonthlyquotesrangeextended-get
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
      - Global
      - Historical
      - Monthly
      - Quotes
      - Range
      - Extended
  /GetHistoricalMonthlyQuotesRangeAdjusted:
    get:
      summary: Get Historical Monthly Quotes Range Adjusted
      description: This operation returns end of month quotes for a US equity. This
        includes split and dividends adjusted price.
      operationId: postGethistoricalmonthlyquotesrangeadjusted
      x-api-path-slug: gethistoricalmonthlyquotesrangeadjusted-get
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
      - Monthly
      - Quotes
      - Range
      - Adjusted
  /GetHistoricalMonthlyQuotesRange:
    get:
      summary: Get Historical Monthly Quotes Range
      description: This operation returns end of month quotes for a US equity. This
        includes split adjusted price.
      operationId: postGethistoricalmonthlyquotesrange
      x-api-path-slug: gethistoricalmonthlyquotesrange-get
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
      - Monthly
      - Quotes
      - Range
  /GetMonthlyTreasuryAverage:
    get:
      summary: Get Monthly Treasury Average
      description: Returns a daily average rate as of a specific date
      operationId: postGetmonthlytreasuryaverage
      x-api-path-slug: getmonthlytreasuryaverage-get
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
      - Monthly
      - Treasury
      - Average
  /GetHistoricalMonthlyVWAP:
    get:
      summary: Get Historical Monthly VWAP
      description: Returns historical monthly VWAP information for a date range.
      operationId: GetHistoricalMonthlyVWAP
      x-api-path-slug: gethistoricalmonthlyvwap-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Monthly
      - VWAP
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