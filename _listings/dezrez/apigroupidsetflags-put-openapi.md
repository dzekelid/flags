---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Sets the interest flags on groups interest role.
  version: 1.0.0
  description: Sets the interest flags on groups interest role..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/group/{id}/setflags:
    put:
      summary: Sets the interest flags on groups interest role.
      description: Sets the interest flags on groups interest role..
      operationId: Group_SetInterestFlagsByidByflagsDataContract
      x-api-path-slug: apigroupidsetflags-put
      parameters:
      - in: body
        name: flagsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Interest
      - Flags
      - "On"
      - Groups
      - Interest
      - Role
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