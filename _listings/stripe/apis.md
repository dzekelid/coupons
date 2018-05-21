---
name: Stripe
x-slug: stripe
description: 'Stripe is a simple, developer-friendly way to accept payments online.
  They believe that enabling transactions on the web is a problem rooted in code,
  not finance, and they want to help put more websites in business. '
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
x-kinRank: "10"
x-alexaRank: ""
tags: Coupons
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Get Coupons
  x-api-slug: stripe
  description: Returns a list of your coupons.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons
  tags: Coupons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/coupons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/coupons-get-openapi.md
- name: Stripe Add Coupons
  x-api-slug: stripe
  description: "You can create coupons easily via the coupon management page of the
    Stripe dashboard. Coupon creation is also accessible via the API if you need to
    create coupons on the fly.A coupon has either a percent_off or an amount_off and
    currency. If you set an amount_off, that amount will be subtracted from any invoice\u2019s
    subtotal. For example, an invoice with a subtotal of 100 will have a final total
    of 0 if a coupon with an amount_off of 200 is applied to it and an invoice with
    a subtotal of 300 will have a final total of 100 if a coupon with an amount_off
    of 200 is applied to it."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons
  tags: Coupons
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/coupons-post-openapi.md
- name: Stripe Delete Coupons Coupon
  x-api-slug: stripe
  description: "You can delete coupons via the coupon management page of the Stripe
    dashboard. However, deleting a coupon does not affect any customers who have already
    applied the coupon; it means that new customers can\u2019t redeem the coupon.
    You can also delete coupons via the API."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/couponscoupon-delete-openapi.md
- name: Stripe Get Coupons Coupon
  x-api-slug: stripe
  description: Retrieves the coupon with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/couponscoupon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/couponscoupon-get-openapi.md
- name: Stripe Add Coupons Coupon
  x-api-slug: stripe
  description: Updates the metadata of a coupon. Other coupon details (currency, duration,
    amount_off) are, by design, not editable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/couponscoupon-post-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Coupons
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/coupons/master/_listings/stripe/openapi.md
x-common:
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---