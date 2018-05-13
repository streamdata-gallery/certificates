---
swagger: "2.0"
info:
  title: AWS Internet of Things API List Certificates By C A
  version: 1.0.0
  description: List the device certificates signed by the specified CA certificate.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListCertificatesByCA:
    get:
      summary: ' List Certificates By C A '
      description: List the device certificates signed by the specified CA certificate
      operationId: listCertificatesByCA
      parameters:
      - in: query
        name: ascendingOrder
        description: Specifies the order for results
        type: string
      - in: query
        name: caCertificateId
        description: The ID of the CA certificate
        type: string
      - in: query
        name: marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: pageSize
        description: The result page size
        type: string
      responses:
        200:
          description: OK
      tags:
      - ca certificates
definitions: []
x-collection-name: AWS Internet of Things
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