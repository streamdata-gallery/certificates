---
swagger: "2.0"
x-collection-name: AWS Certificate Manager
x-complete: 0
info:
  title: AWS Certificate Manager API Get Certificate
  version: 1.0.0
  description: |-
    Retrieves an ACM Certificate and certificate chain for the certificate specified by an
          ARN.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteCertificate:
    get:
      summary: Delete Certificate
      description: Deletes an ACM Certificate and its associated private key.
      operationId: DeleteCertificate
      x-api-path-slug: actiondeletecertificate-get
      parameters:
      - in: query
        name: CertificateArn
        description: String that contains the ARN of the ACM Certificate to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /?Action=DescribeCertificate:
    get:
      summary: Describe Certificate
      description: Returns a list of the fields contained in the specified ACM Certificate.
      operationId: DescribeCertificate
      x-api-path-slug: actiondescribecertificate-get
      parameters:
      - in: query
        name: CertificateArn
        description: String that contains an ACM Certificate ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /?Action=GetCertificate:
    get:
      summary: Get Certificate
      description: |-
        Retrieves an ACM Certificate and certificate chain for the certificate specified by an
              ARN.
      operationId: GetCertificate
      x-api-path-slug: actiongetcertificate-get
      parameters:
      - in: query
        name: CertificateArn
        description: 'String that contains a certificate ARN in the following format:'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
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