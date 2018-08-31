{
  "info": {
    "name": "Okta Deactivate User",
    "_postman_id": "72b63c23-c0ae-4ab7-8d60-709f4ba54b5a",
    "description": "Deactivate user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Deactivate",
      "item": [
        {
          "id": "31b9ea03-3c26-4bda-b3e5-696f68d7c016",
          "name": "postUsersUserLifecycleDeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId/lifecycle/deactivate"
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
            "description": "Deactivate user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69a9bfab-c582-4c0a-99e5-6c0be8927da4"
            }
          ]
        }
      ]
    }
  ]
}