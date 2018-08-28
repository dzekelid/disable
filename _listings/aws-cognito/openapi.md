swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AdminDisableUser:
    get:
      summary: Admin Disable User
      description: Disables the specified user as an administrator.
      operationId: adminDisableUser
      x-api-path-slug: actionadmindisableuser-get
      parameters:
      - in: query
        name: Username
        description: The user name of the user you wish to disable
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to disable
          the user
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users