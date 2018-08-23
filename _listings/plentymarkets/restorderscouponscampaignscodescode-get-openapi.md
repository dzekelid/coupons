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
  /rest/orders/coupons/campaigns/{campaignId}/codes:
    post:
      summary: Create a coupon code
      description: Creates a coupon code. The ID of the campaign must be specified.
        A code can optionally be specified. A random code will be generated if the
        code is not specified. A coupon value can also be optionally specified. The
        value of the campaign will be used if no individual value is specified.
      operationId: postRestOrdersCouponsCampaignsCampaignCodes
      x-api-path-slug: restorderscouponscampaignscampaignidcodes-post
      parameters:
      - in: body
        name: /rest/orders/coupons/campaigns/{campaignId}/codes
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: campaignId
      responses:
        200:
          description: OK
      tags:
      - Coupon
      - Code
  /rest/orders/coupons/codes/contacts/{contactId}:
    get:
      summary: List redeemed coupon codes of a contact
      description: Lists the redeemed coupon codes of contact. The ID of the contact
        must be specified.
      operationId: getRestOrdersCouponsCodesContactsContact
      x-api-path-slug: restorderscouponscodescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of coupons to be displayed per page
      - in: query
        name: page
        description: The page to get
      responses:
        200:
          description: OK
      tags:
      - List
      - Redeemed
      - Coupon
      - Codes
      - Of
      - Contact
  /rest/orders/coupons/codes/{coupon}:
    post:
      summary: Validate a coupon
      description: Validates if a coupon code can be used for the specified items,
        contact ID, etc. The code must be specified. If the coupon code is invalid,
        a ValidationException will be thrown. If the coupon code is valid, a CouponCodeValidation
        object will be returned.
      operationId: postRestOrdersCouponsCodesCoupon
      x-api-path-slug: restorderscouponscodescoupon-post
      parameters:
      - in: body
        name: /rest/orders/coupons/codes/{coupon}
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: callFromScheduler
        description: Flag that indicates whether the validation is requested by a
          subscription order or not
      - in: query
        name: contactClass
        description: The contact class
      - in: query
        name: contactType
        description: The contact type
      - in: path
        name: coupon
      - in: query
        name: plentyId
        description: The plenty id
      - in: query
        name: shipToCountry
        description: The country of delivery
      - in: query
        name: taxIdNumber
        description: The tax id number
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Coupon
  /rest/orders/{orderId}/coupons/{coupon}:
    post:
      summary: Redeem a coupon code
      description: Redeems a coupon code and applies it to an order. The ID of the
        order must be specified. If the coupon was successfully redeemed, the coupon
        data will be returned. If the coupon can not be redeemed, a validation exception
        will be thrown.
      operationId: postRestOrdersOrderCouponsCoupon
      x-api-path-slug: restordersorderidcouponscoupon-post
      parameters:
      - in: path
        name: coupon
      - in: path
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - Redeem
      - Coupon
      - Code
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