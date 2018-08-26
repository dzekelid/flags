---
swagger: "2.0"
x-collection-name: Google Cloud SQL
x-complete: 1
info:
  title: Cloud SQL Administration
  description: creates-and-configures-cloud-sql-instances-which-provide-fullymanaged-mysql-databases-
  contact:
    name: Google
    url: https://google.com
  version: v1beta4
host: www.googleapis.com
basePath: /sql/v1beta4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /flags:
    get:
      summary: Get Flags
      description: List all available database flags for Google Cloud SQL instances.
      operationId: sql.flags.list
      x-api-path-slug: flags-get
      parameters:
      - in: query
        name: databaseVersion
        description: Database version for flag retrieval
      responses:
        200:
          description: OK
      tags:
      - Flags
---