{
  "info": {
    "name": "Plentymarkets Delete a coupon",
    "_postman_id": "59078dd5-5ca4-4b67-a50f-5e65d9f5f21c",
    "description": "Deletes a coupon by the coupon code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Coupon",
      "item": [
        {
          "id": "d5cc8d59-8b9f-4377-ae6a-5d58603cb8e0",
          "name": "deleteRestOrdersCouponsCampaignsCodesCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/coupons/campaigns/codes/:code"
              ],
              "query": [
                {
                  "key": "withoutUsed",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a coupon by the coupon code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e9a5c68-a792-4cb8-84a7-793e51980bcc"
            }
          ]
        }
      ]
    }
  ]
}