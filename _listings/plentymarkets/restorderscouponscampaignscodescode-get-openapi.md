---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get coupon code information
  description: Gets coupon code information. The code must be specified.
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
  /rest/orders/coupons/campaigns/codes/{code}:
    delete:
      summary: Delete a coupon
      description: Deletes a coupon by the coupon code.
      operationId: deleteRestOrdersCouponsCampaignsCodesCode
      x-api-path-slug: restorderscouponscampaignscodescode-delete
      parameters:
      - in: path
        name: code
      - in: query
        name: withoutUsed
        description: Do not delete used coupons
      responses:
        200:
          description: OK
      tags:
      - Coupon
    get:
      summary: Get coupon code information
      description: Gets coupon code information. The code must be specified.
      operationId: getRestOrdersCouponsCampaignsCodesCode
      x-api-path-slug: restorderscouponscampaignscodescode-get
      parameters:
      - in: path
        name: code
      - in: query
        name: with
        description: Load additional relations for a coupon code
      responses:
        200:
          description: OK
      tags:
      - Coupon
      - Code
      - Information
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