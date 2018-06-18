{
  "info": {
    "name": "US Yellow Pages Get Coupons",
    "_postman_id": "ac88b0ca-b3e8-4ec8-a85c-6f7784c345fc",
    "description": "Returns coupons near the submitted location. Optionally, a term parameter can be submitted to restrict coupons to relevant categories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Coupons",
      "item": [
        {
          "id": "e9ce69a1-dfd1-4288-ba2e-8fb9a5bc71c6",
          "name": "getCoupons",
          "request": {
            "url": "http://api2.yp.com/content/v1/coupons?format=%7B%7D&searchloc=%7B%7D&term=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns coupons near the submitted location. Optionally, a term parameter can be submitted to restrict coupons to relevant categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e90f2a4e-ff27-4bd3-9ce8-f521b78c41de"
            }
          ]
        }
      ]
    }
  ]
}