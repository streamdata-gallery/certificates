---
swagger: "2.0"
x-collection-name: AWS API Gateway
x-complete: 0
info:
  title: AWS API Gateway API Clientcertificate Byid
  version: 1.0.0
  description: Gets the ClientCertificate resource with the specified identifier.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /clientcertificates/9ao60f:
    get:
      summary: Clientcertificate Byid
      description: Gets the ClientCertificate resource with the specified identifier.
      operationId: clientcertificateBy-id
      x-api-path-slug: clientcertificates9ao60f-get
      parameters:
      - in: header
        name: Authorization
        type: string
      - in: header
        name: Content-Type
        type: string
      - in: header
        name: Host
        type: string
      - in: header
        name: X-Amz-Date
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
      - Byid
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