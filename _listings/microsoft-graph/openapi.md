swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbooknamesltnamegtrangeformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/font:
    get:
      summary: Get Range Font
      description: Get RangeFont Retrieve the properties and relationships of rangefont
        object.
      operationId: GetRangeFont
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfont-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Font