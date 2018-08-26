---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /listings/{slug}/flag:
    post:
      summary: Post Listings Slug Flag
      description: Flag a listing for inappropriate content or fraud
      operationId: postListingsSlugFlag
      x-api-path-slug: listingsslugflag-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Flag
---