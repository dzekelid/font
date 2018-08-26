---
swagger: "2.0"
x-collection-name: Google Fonts
x-complete: 0
info:
  title: Google Fonts API Get Web Fonts
  description: Retrieves the list of fonts currently served by the Google Fonts Developer
    API
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /webfonts/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webfonts:
    get:
      summary: Get Web Fonts
      description: Retrieves the list of fonts currently served by the Google Fonts
        Developer API
      operationId: webfonts.webfonts.list
      x-api-path-slug: webfonts-get
      parameters:
      - in: query
        name: sort
        description: Enables sorting of the list
      responses:
        200:
          description: OK
      tags:
      - Font
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