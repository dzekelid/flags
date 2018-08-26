---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/todo/completetask:
    put:
      summary: If Due Date is not populated a complete flag is set or if Due Date
        is populated a recurrence is set
      description: If due date is not populated a complete flag is set or if due date
        is populated a recurrence is set.
      operationId: DefaultToDo_CompleteTaskBycompleteTask
      x-api-path-slug: apitodocompletetask-put
      parameters:
      - in: body
        name: completeTask
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - If
      - Due
      - Date
      - Is
      - Not
      - Populated
      - Complete
      - Flag
      - Is
      - Set
      - If
      - Due
      - Date
      - Is
      - Populated
      - Recurrence
      - Is
      - Set
  /api/role/{id}/setflag:
    put:
      summary: Sets a flag on a property marketing role
      description: Sets a flag on a property marketing role.
      operationId: Role_SetFlagByidBysetMarketingFlagDataContract
      x-api-path-slug: apiroleidsetflag-put
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setMarketingFlagDataContract
        description: The flag detail
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Flag
      - "On"
      - Property
      - Marketing
      - Role
---