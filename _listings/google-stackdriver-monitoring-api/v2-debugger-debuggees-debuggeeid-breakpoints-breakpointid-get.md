---
swagger: "2.0"
info:
  title: Google Stackdriver Monitoring API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/debugger/debuggees/{debuggeeId}/breakpoints/{breakpointId}:
    get:
      summary: ""
      description: Gets breakpoint information
      operationId: clouddebugger.debugger.debuggees.breakpoints.get
      parameters:
      - in: path
        name: breakpointId
        description: ID of the breakpoint to get
      - in: query
        name: clientVersion
        description: The client version making the call
      - in: path
        name: debuggeeId
        description: ID of the debuggee whose breakpoint to get
      responses:
        200:
          description: OK
      tags:
      - debugger
definitions: []
x-collection-name: Google Stackdriver Monitoring API
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