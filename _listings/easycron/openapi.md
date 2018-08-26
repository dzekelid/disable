---
swagger: "2.0"
x-collection-name: EasyCron
x-complete: 1
info:
  title: Easycron API
  description: all-registered-users-of-easycron-can-utilize-our-api-to-manage-their-cron-jobs-without-logging-in-easycron-com-
  termsOfService: https://www.easycron.com/terms
  contact:
    name: EasyCron
    url: https://www.easycron.com/contact
  version: 1.0.0
host: www.easycron.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /disable:
    get:
      summary: Disable a cron job
      description: Disable a cron job
      operationId: disableCronJbo
      x-api-path-slug: disable-get
      parameters:
      - in: query
        name: id
        description: ID of the cron job you want to disable
      - in: query
        name: token
        description: You API token
      responses:
        200:
          description: OK
      tags:
      - Disable
      - Cron
      - Job
---