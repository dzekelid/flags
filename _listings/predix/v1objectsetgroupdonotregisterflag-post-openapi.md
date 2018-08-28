---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Fingerprint of Things Object Tagging Service Switch Apply Flag per
    Group
  description: '* DO NOT USE. This API will be deleted.<br>Switch the Apply flag per
    group'
  contact:
    name: NEC
  version: 1.0.0
host: fingerprint-of-things-ga1-dast.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/object/setObjectDoNotRegisterFlag:
    post:
      summary: Switch Apply Flag
      description: '* DO NOT USE. This API will be deleted.<br>Switch the Apply flag
        on or off.'
      operationId: config
      x-api-path-slug: v1objectsetobjectdonotregisterflag-post
      parameters:
      - in: header
        name: 'Authorization: Bearer'
        description: OAuth2 token
      - in: body
        name: body
        description: Request body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Predix-Zone-Id
        description: Zone ID
      responses:
        200:
          description: OK
      tags:
      - Switch
      - Apply
      - Flag
  /v1/object/setGroupDoNotRegisterFlag:
    post:
      summary: Switch Apply Flag per Group
      description: '* DO NOT USE. This API will be deleted.<br>Switch the Apply flag
        per group'
      operationId: groupConfig
      x-api-path-slug: v1objectsetgroupdonotregisterflag-post
      parameters:
      - in: header
        name: 'Authorization: Bearer'
        description: OAuth2 token
      - in: body
        name: body
        description: Request body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Predix-Zone-Id
        description: Zone ID
      responses:
        200:
          description: OK
      tags:
      - Switch
      - Apply
      - Flag
      - Per
      - Group
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