---
swagger: "2.0"
x-collection-name: AWS CloudWatch
x-complete: 1
info:
  title: AWS CloudWatch API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisableAlarmActions:
    "":
      summary: Disable Alarm Actions
      description: Disables the actions for the specified alarms.
      operationId: disablealarmactions
      x-api-path-slug: actiondisablealarmactions-
      parameters:
      - in: query
        name: AlarmNames.member.N
        description: The names of the alarms
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alarm Actions
---