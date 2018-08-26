---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Baseentry Action Flag
  description: Flag inappropriate entry for moderation.
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/baseentry/action/flag:
    get:
      summary: Get Service Baseentry Action Flag
      description: Flag inappropriate entry for moderation.
      operationId: baseEntry.flag
      x-api-path-slug: servicebaseentryactionflag-get
      parameters:
      - in: query
        name: moderationFlag[comments]
        description: The comment that was added to the flag
      - in: query
        name: moderationFlag[flaggedEntryId]
        description: If moderation flag is set for entry, this is the flagged entry
          id
      - in: query
        name: moderationFlag[flaggedUserId]
        description: If moderation flag is set for user, this is the flagged user
          id
      - in: query
        name: moderationFlag[flagType]
        description: 'Enum Type: `KalturaModerationFlagType`'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - Flag
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