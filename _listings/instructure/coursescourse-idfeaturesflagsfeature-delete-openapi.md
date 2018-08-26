---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Remove feature flag
  description: Remove feature flag.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/features/flags/feature:
    delete:
      summary: Remove feature flag
      description: Remove feature flag.
      operationId: remove-feature-flag
      x-api-path-slug: coursescourse-idfeaturesflagsfeature-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Features
      - Flags
      - Feature
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