---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Historical Get Global Historical Monthly Quotes Range
  description: This operation returns a range of monthly quotes for an equity based
    on the specified date range. This includes the adjusted price as specified.
  version: 1.0.0
host: www.xignite.com
basePath: xGlobalHistorical.json/XigniteGlobalHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetGlobalHistoricalMonthlyQuotesRange:
    post:
      summary: Get Global Historical Monthly Quotes Range
      description: This operation returns a range of monthly quotes for an equity
        based on the specified date range. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalmonthlyquotesrange
      x-api-path-slug: getglobalhistoricalmonthlyquotesrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Monthly
      - Quotes
      - Range
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