---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Request Requestid Condition Travel
  version: 1.0.0
  description: Post request requestid condition travel.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/request/{requestId}/condition/travel:
    get:
      summary: Get Request Requestid Condition Travel
      description: Get request requestid condition travel.
      operationId: getApiV1RequestRequestConditionTravel
      x-api-path-slug: apiv1requestrequestidconditiontravel-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Travel
    post:
      summary: Post Request Requestid Condition Travel
      description: Post request requestid condition travel.
      operationId: postApiV1RequestRequestConditionTravel
      x-api-path-slug: apiv1requestrequestidconditiontravel-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Travel
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