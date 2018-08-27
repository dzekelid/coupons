---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Coupons
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Delete a coupon
  x-api-slug: restorderscouponscampaignscodescode-delete
  description: Deletes a coupon by the coupon code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-openapi.md
- name: plentymarkets REST-API - Get coupon code information
  x-api-slug: restorderscouponscampaignscodescode-get
  description: Gets coupon code information. The code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-openapi.md
- name: plentymarkets REST-API - Disable or enable coupon
  x-api-slug: restorderscouponscampaignscodescodedisabledisdisabled-put
  description: Sets the coupon disable field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-openapi.md
- name: plentymarkets REST-API - Create a coupon code
  x-api-slug: restorderscouponscampaignscampaignidcodes-post
  description: Creates a coupon code. The ID of the campaign must be specified. A
    code can optionally be specified. A random code will be generated if the code
    is not specified. A coupon value can also be optionally specified. The value of
    the campaign will be used if no individual value is specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscampaignidcodes-post-openapi.md
- name: plentymarkets REST-API - List redeemed coupon codes of a contact
  x-api-slug: restorderscouponscodescontactscontactid-get
  description: Lists the redeemed coupon codes of contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Validate a coupon
  x-api-slug: restorderscouponscodescoupon-post
  description: Validates if a coupon code can be used for the specified items, contact
    ID, etc. The code must be specified. If the coupon code is invalid, a ValidationException
    will be thrown. If the coupon code is valid, a CouponCodeValidation object will
    be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescoupon-post-openapi.md
- name: plentymarkets REST-API - Redeem a coupon code
  x-api-slug: restordersorderidcouponscoupon-post
  description: Redeems a coupon code and applies it to an order. The ID of the order
    must be specified. If the coupon was successfully redeemed, the coupon data will
    be returned. If the coupon can not be redeemed, a validation exception will be
    thrown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restordersorderidcouponscoupon-post-openapi.md
- name: plentymarkets REST-API - Delete a coupon
  x-api-slug: restorderscouponscampaignscodescode-delete
  description: Deletes a coupon by the coupon code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-openapi.md
- name: plentymarkets REST-API - Get coupon code information
  x-api-slug: restorderscouponscampaignscodescode-get
  description: Gets coupon code information. The code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-openapi.md
- name: plentymarkets REST-API - Disable or enable coupon
  x-api-slug: restorderscouponscampaignscodescodedisabledisdisabled-put
  description: Sets the coupon disable field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-openapi.md
- name: plentymarkets REST-API - Create a coupon code
  x-api-slug: restorderscouponscampaignscampaignidcodes-post
  description: Creates a coupon code. The ID of the campaign must be specified. A
    code can optionally be specified. A random code will be generated if the code
    is not specified. A coupon value can also be optionally specified. The value of
    the campaign will be used if no individual value is specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscampaignidcodes-post-openapi.md
- name: plentymarkets REST-API - List redeemed coupon codes of a contact
  x-api-slug: restorderscouponscodescontactscontactid-get
  description: Lists the redeemed coupon codes of contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Validate a coupon
  x-api-slug: restorderscouponscodescoupon-post
  description: Validates if a coupon code can be used for the specified items, contact
    ID, etc. The code must be specified. If the coupon code is invalid, a ValidationException
    will be thrown. If the coupon code is valid, a CouponCodeValidation object will
    be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescoupon-post-openapi.md
- name: plentymarkets REST-API - Redeem a coupon code
  x-api-slug: restordersorderidcouponscoupon-post
  description: Redeems a coupon code and applies it to an order. The ID of the order
    must be specified. If the coupon was successfully redeemed, the coupon data will
    be returned. If the coupon can not be redeemed, a validation exception will be
    thrown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restordersorderidcouponscoupon-post-openapi.md
- name: plentymarkets REST-API - Redeem a coupon code
  x-api-slug: restordersorderidcouponscoupon-post
  description: Redeems a coupon code and applies it to an order. The ID of the order
    must be specified. If the coupon was successfully redeemed, the coupon data will
    be returned. If the coupon can not be redeemed, a validation exception will be
    thrown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restordersorderidcouponscoupon-post-openapi.md
- name: plentymarkets REST-API - Validate a coupon
  x-api-slug: restorderscouponscodescoupon-post
  description: Validates if a coupon code can be used for the specified items, contact
    ID, etc. The code must be specified. If the coupon code is invalid, a ValidationException
    will be thrown. If the coupon code is valid, a CouponCodeValidation object will
    be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescoupon-post-openapi.md
- name: plentymarkets REST-API - List redeemed coupon codes of a contact
  x-api-slug: restorderscouponscodescontactscontactid-get
  description: Lists the redeemed coupon codes of contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscodescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Create a coupon code
  x-api-slug: restorderscouponscampaignscampaignidcodes-post
  description: Creates a coupon code. The ID of the campaign must be specified. A
    code can optionally be specified. A random code will be generated if the code
    is not specified. A coupon value can also be optionally specified. The value of
    the campaign will be used if no individual value is specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscampaignidcodes-post-openapi.md
- name: plentymarkets REST-API - Disable or enable coupon
  x-api-slug: restorderscouponscampaignscodescodedisabledisdisabled-put
  description: Sets the coupon disable field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-openapi.md
- name: plentymarkets REST-API - Get coupon code information
  x-api-slug: restorderscouponscampaignscodescode-get
  description: Gets coupon code information. The code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-openapi.md
- name: plentymarkets REST-API - Delete a coupon
  x-api-slug: restorderscouponscampaignscodescode-delete
  description: Deletes a coupon by the coupon code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---