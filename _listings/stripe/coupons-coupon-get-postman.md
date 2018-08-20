{
  "info": {
    "name": "Stripe Get Coupons Coupon",
    "_postman_id": "1df9377a-da20-4672-a93a-796262847df8",
    "description": "Retrieves the coupon with the given ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "coupons",
      "item": [
        {
          "id": "6762288f-9b8f-4fb5-bab6-e8d006484133",
          "name": "getCouponsCoupon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "coupons/:coupon"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "coupon",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the coupon with the given ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e1fac98-ad08-4367-8e14-4bee2d66292a"
            }
          ]
        }
      ]
    }
  ]
}