---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Event Comment Flag
  description: This method creates a spam report for comment content
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2/event_comment_flag:
    post:
      summary: Event Comment Flag
      description: This method creates a spam report for comment content
      operationId: events
      x-api-path-slug: 2event-comment-flag-post
      parameters:
      - in: query
        name: comment_id
        description: The id of the comment
        type: string
      - in: query
        name: reason
        description: Reason for flagging the comment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
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