---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Disable Vgw Route Propagation
  version: 1.0.0
  description: Disables a virtual private gateway (VGW) from propagating routes to
    a specified route table of a VPC.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisableVgwRoutePropagation:
    get:
      summary: Disable Vgw Route Propagation
      description: Disables a virtual private gateway (VGW) from propagating routes
        to a specified route table of a VPC.
      operationId: disablevgwroutepropagation
      x-api-path-slug: actiondisablevgwroutepropagation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID representing the current association between
          the route table and subnet
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual Private Gateway
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