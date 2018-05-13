---
swagger: "2.0"
info:
  title: AWS Internet of Things API Update Certificate
  version: 1.0.0
  description: Updates the status of the specified certificate.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateCertificate:
    get:
      summary: ' Update Certificate '
      description: Updates the status of the specified certificate
      operationId: updateCertificate
      parameters:
      - in: query
        name: certificateId
        description: The ID of the certificate
        type: string
      - in: query
        name: newStatus
        description: The new status
        type: string
      responses:
        200:
          description: OK
      tags:
      - certificates
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