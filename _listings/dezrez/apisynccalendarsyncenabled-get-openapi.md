---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: "Dezrez check if the calendar sync is enabled for this user\r\nthis could
    be used to enabled/disable the calendar setup button"
  version: 1.0.0
  description: "Check if the calendar sync is enabled for this user\r\nthis could
    be used to enabled/disable the calendar setup button."
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/calendarsyncenabled:
    get:
      summary: "check if the calendar sync is enabled for this user\r\nthis could
        be used to enabled/disable the calendar setup button"
      description: "Check if the calendar sync is enabled for this user\r\nthis could
        be used to enabled/disable the calendar setup button."
      operationId: Sync_CalendarSyncEnabled
      x-api-path-slug: apisynccalendarsyncenabled-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Check
      - If
      - Calendar
      - Sync
      - Is
      - Enabledthis
      - "User\r\nThis"
      - Could
      - Be
      - Used
      - To
      - Enabled
      - Disable
      - Calendar
      - Setup
      - Button
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