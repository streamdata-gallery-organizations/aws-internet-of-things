---
swagger: "2.0"
info:
  title: AWS Internet of Things API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeCACertificate:
    get:
      summary: ' Describe C A Certificate '
      description: Describes a registered CA certificate
      operationId: describeCACertificate
      parameters:
      - in: query
        name: certificateId
        description: The CA certificate identifier
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