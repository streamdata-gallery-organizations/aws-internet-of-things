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
  /?Action=DeleteThing:
    get:
      summary: ' Delete Thing '
      description: Deletes the specified thing
      operationId: deleteThing
      parameters:
      - in: query
        name: expectedVersion
        description: The expected version of the thing record in the registry
        type: string
      - in: query
        name: thingName
        description: The name of the thing to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - things
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