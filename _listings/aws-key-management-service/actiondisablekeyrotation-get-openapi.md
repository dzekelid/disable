---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 0
info:
  title: AWS Key Management Service API Disable Key Rotation
  version: 1.0.0
  description: Disables rotation of the specified key.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisableKey:
    get:
      summary: Disable Key
      description: |-
        Sets the state of a customer master key (CMK) to disabled, thereby preventing its use
              for cryptographic operations.
      operationId: disableKey
      x-api-path-slug: actiondisablekey-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the CMK
        type: string
      responses:
        200:
          description: OK
      tags:
      - Keys
  /?Action=DisableKeyRotation:
    get:
      summary: Disable Key Rotation
      description: Disables rotation of the specified key.
      operationId: disableKeyRotation
      x-api-path-slug: actiondisablekeyrotation-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the customer master key
        type: string
      responses:
        200:
          description: OK
      tags:
      - Keys
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