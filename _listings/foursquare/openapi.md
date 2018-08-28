swagger: "2.0"
x-collection-name: Foursquare
x-complete: 1
info:
  title: Foursquare
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /specials/{ID}/flag:
    post:
      summary: Post Specials Flag
      description: /specials/{SPECIAL_ID}/configuration
      operationId: specialsspecial-idconfiguration
      x-api-path-slug: specialsidflag-post
      parameters:
      - in: query
        name: ID
        description: The id of the special being flagged
      - in: path
        name: ID
      - in: query
        name: problem
        description: One of not_redeemable, not_valuable, other
      - in: query
        name: text
        description: Additional text about why the user has flagged this special
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: venueId
        description: The id of the venue running the special
      responses:
        200:
          description: OK
      tags:
      - Specials
      - Flag
  /venues/{VENUE_ID}/flag:
    post:
      summary: Post Venues Flag
      description: /venues/{VENUE_ID}/edit
      operationId: venuesvenue-idedit
      x-api-path-slug: venuesvenue-idflag-post
      parameters:
      - in: query
        name: problem
        description: One of mislocated, closed, duplicate, inappropriate, doesnt_exist,
          event_over
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: venueId
        description: ID of the duplicated venue (for problem duplicate)
      - in: query
        name: VENUE_ID
        description: The venue id for which an edit is being proposed
      - in: path
        name: VENUE_ID
      responses:
        200:
          description: OK
      tags:
      - Venues
      - Flag