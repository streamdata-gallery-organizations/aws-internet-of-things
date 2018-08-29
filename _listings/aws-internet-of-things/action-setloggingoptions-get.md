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
  /?Action=SetLoggingOptions:
    get:
      summary: ' Set Logging Options '
      description: Sets the logging options
      operationId: setLoggingOptions
      parameters:
      - in: query
        name: loggingOptionsPayload
        description: The logging options payload
        type: string
      responses:
        200:
          description: OK
      tags:
      - logging
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