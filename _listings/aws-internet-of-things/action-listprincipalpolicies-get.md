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
  /?Action=ListPrincipalPolicies:
    get:
      summary: ' List Principal Policies '
      description: Lists the policies attached to the specified principal
      operationId: listPrincipalPolicies
      parameters:
      - in: query
        name: ascendingOrder
        description: Specifies the order for results
        type: string
      - in: query
        name: marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: pageSize
        description: The result page size
        type: string
      - in: query
        name: principal
        description: The principal
        type: string
      responses:
        200:
          description: OK
      tags:
      - principal policies
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