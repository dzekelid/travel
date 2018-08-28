swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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