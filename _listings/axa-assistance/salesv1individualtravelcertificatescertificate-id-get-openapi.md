---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Gets the travel certificate details.
  description: Gets the travel certificate details.
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