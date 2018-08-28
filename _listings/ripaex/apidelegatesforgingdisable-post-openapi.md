---
swagger: "2.0"
x-collection-name: RipaEx
x-complete: 0
info:
  title: RipaEx Delegates Forging Disable
  description: Disable forging for a delegate.
  version: 1.0.0
host: api.ripaex.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/delegates/forging/disable:
    post:
      summary: Delegates Forging Disable
      description: Disable forging for a delegate.
      operationId: delegates.disableForging
      x-api-path-slug: apidelegatesforgingdisable-post
      parameters:
      - in: query
        name: publicKey
        description: A valid RIPA Public Key
      - in: query
        name: secret
        description: A valid RIPA Passphrase
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Delegates
      - Forging
      - Disable
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