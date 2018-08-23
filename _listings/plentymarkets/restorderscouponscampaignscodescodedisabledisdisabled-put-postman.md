{
  "info": {
    "name": "Plentymarkets Disable or enable coupon",
    "_postman_id": "9196fc29-e0ef-4d7d-942a-9a777db8936c",
    "description": "Sets the coupon disable field.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Coupon",
      "item": [
        {
          "id": "71fd24b5-dd46-482f-9be1-098666183e97",
          "name": "getRestOrdersCouponsCampaignsCodesCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/coupons/campaigns/codes/:code"
              ],
              "query": [
                {
                  "key": "with",
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
            "method": "GET",
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
            "description": "Gets coupon code information. The code must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e20dc77-b7d1-46c8-845b-50f866a4197b"
            }
          ]
        },
        {
          "id": "dab6a07b-3f9c-4ec1-8135-1fb66ba6cf5a",
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
              "id": "35aecbb2-2f22-4c99-a11c-7ab68618adaa"
            }
          ]
        }
      ]
    },
    {
      "name": "Disable",
      "item": [
        {
          "id": "0a9f2104-671c-4ade-9d78-eee639514290",
          "name": "putRestOrdersCouponsCampaignsCodesCodeDisabledIsdisabled",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/coupons/campaigns/codes/:code/disabled/:isDisabled"
              ],
              "variable": [
                {
                  "id": "code",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "isDisabled",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
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
            "description": "Sets the coupon disable field."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6d9b581-7339-400b-9c55-3b05bee6d072"
            }
          ]
        }
      ]
    }
  ]
}