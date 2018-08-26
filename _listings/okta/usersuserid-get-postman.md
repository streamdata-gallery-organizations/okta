{
  "info": {
    "name": "Okta Get User",
    "_postman_id": "20b80cf3-0a30-41ba-ad74-a130286611ed",
    "description": "Get user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "84b32594-face-4f2c-8ecb-40fde3c2fb31",
          "name": "getUsersUser",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId"
              ],
              "variable": [
                {
                  "id": "userId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
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
            "description": "Get user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b899e2f-2637-4600-9111-6d81da82e854"
            }
          ]
        }
      ]
    }
  ]
}