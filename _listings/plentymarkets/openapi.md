---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/orders/coupons/campaigns/codes/{code}/disabled/{isDisabled}:
    put:
      summary: Disable or enable coupon
      description: Sets the coupon disable field.
      operationId: putRestOrdersCouponsCampaignsCodesCodeDisabledIsdisabled
      x-api-path-slug: restorderscouponscampaignscodescodedisabledisdisabled-put
      parameters:
      - in: path
        name: code
      - in: path
        name: isDisabled
      responses:
        200:
          description: OK
      tags:
      - Disable
      - Enable
      - Coupon
---