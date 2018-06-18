---
swagger: "2.0"
x-collection-name: Zendesk
x-complete: 1
info:
  title: Sales Force Desk API
  description: build-deep-integrations-expose-your-service-to-influential-smb-customers-or-just-make-desk-com-work-the-way-you-want-
  version: v2
host: yoursite.desk.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cases.{format}:
    get:
      summary: Get Cases
      description: Get cases.
      operationId: get-cases
      x-api-path-slug: cases-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
  /cases/{id}.{format}:
    get:
      summary: Get Case
      description: Get case.
      operationId: get-case
      x-api-path-slug: casesid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
    put:
      summary: Update Case
      description: Update case.
      operationId: update-case
      x-api-path-slug: casesid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
---