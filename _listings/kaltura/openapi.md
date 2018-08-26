---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
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
---