{
  "info": {
    "name": "Okta Suspend User",
    "_postman_id": "72b1e4d3-7b79-4537-99f1-d81ab1508470",
    "description": "Suspend user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Suspend",
      "item": [
        {
          "id": "ec0b274a-3d6d-4f49-b1e8-9d2ae1e04b5e",
          "name": "postUsersUserLifecycleSuspend",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId/lifecycle/suspend"
              ],
              "variable": [
                {
                  "id": "userId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Suspend user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2494ccfc-d1ef-4cc1-8715-99f14e1934ca"
            }
          ]
        }
      ]
    }
  ]
}