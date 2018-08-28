swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/issue/{issueIdOrKey}/editmeta:
    get:
      summary: Get edit issue meta
      description: |-
        Returns the metadata for editing an issue.

        The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

        If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
      operationId: com.atlassian.jira.rest.v2.issue.IssueResource.getEditIssueMeta_get
      x-api-path-slug: api2issueissueidorkeyeditmeta-get
      parameters:
      - in: path
        name: issueIdOrKey
        description: ID or key of the issue
      - in: query
        name: overrideEditableFlag
        description: Allows retrieving edit metadata for fields in non-editable status
          (jira
      - in: query
        name: overrideScreenSecurity
        description: Allows retrieving edit metadata for the fields hidden on Edit
          screen
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Issue
      - Meta