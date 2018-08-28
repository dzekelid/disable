swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 1
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisableRadius:
    get:
      summary: Disable Radius
      description: Disables multi-factor authentication (MFA) with the Remote Authentication
        Dial In User Service (RADIUS) server for an AD Connector directory.
      operationId: disableRadius
      x-api-path-slug: actiondisableradius-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory for which to disable MFA
        type: string
      responses:
        200:
          description: OK
      tags:
      - Radius
  /?Action=DisableSso:
    get:
      summary: Disable Sso
      description: Disables single-sign on for a directory.
      operationId: disableSso
      x-api-path-slug: actiondisablesso-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory for which to disable single-sign
          on
        type: string
      - in: query
        name: Password
        description: The password of an alternate account to use to disable single-sign
          on
        type: string
      - in: query
        name: UserName
        description: The username of an alternate account to use to disable single-sign
          on
        type: string
      responses:
        200:
          description: OK
      tags:
      - SSO