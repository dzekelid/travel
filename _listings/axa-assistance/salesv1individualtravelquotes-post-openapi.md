---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Create new individual travel quote for sales
  description: Create new individual travel quote for sales
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sales/v1/individual/travel/certificates/{certificate_id}:
    get:
      summary: Gets the travel certificate details.
      description: Gets the travel certificate details.
      operationId: getSalesV1IndividualTravelCertificatesCertificate_id
      x-api-path-slug: salesv1individualtravelcertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - travel
      - certificate
      - details.
  /insurance/vexp/travel_accident/claims:
    post:
      summary: Requests to create a claim related to a travel accident.
      description: Requests to create a claim related to a travel accident.
      operationId: postInsuranceVexpTravel_accidentClaims
      x-api-path-slug: insurancevexptravel-accidentclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totravel
      - accident.
  /sales/v1/individual/travel/certificates:
    post:
      summary: Requests the activation of a travel certificate linked to a product.
        At least one product_criteria has to be specified to identify the product
        to which to subscribe. If the user already holds a certificate, this api will
        update its personal informati
      description: Requests the activation of a travel certificate linked to a product.
        At least one product_criteria has to be specified to identify the product
        to which to subscribe. If the user already holds a certificate, this api will
        update its personal informati
      operationId: postSalesV1IndividualTravelCertificates
      x-api-path-slug: salesv1individualtravelcertificates-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - the
      - activation
      - oftravel
      - certificate
      - linked
      - toproduct.
      - At
      - leastproduct_criteria
      - haAssistance
      - to
      - be
      - specified
      - to
      - identify
      - the
      - product
      - to
      - which
      - to
      - subscribe.
      - If
      - the
      - user
      - already
      - holdscertificate
      - ""
      - thiAssistance
      - api
      - will
      - update
      - itAssistance
      - personal
      - informati
  /sales/v1/individual/travel/policies:
    post:
      summary: Create new individual travel policy for sales
      description: Create new individual travel policy for sales
      operationId: postSalesV1IndividualTravelPolicies
      x-api-path-slug: salesv1individualtravelpolicies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - new
      - individual
      - travel
      - policysales
  /sales/v1/individual/travel/quotes:
    post:
      summary: Create new individual travel quote for sales
      description: Create new individual travel quote for sales
      operationId: postSalesV1IndividualTravelQuotes
      x-api-path-slug: salesv1individualtravelquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - new
      - individual
      - travel
      - quotesales
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