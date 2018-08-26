{
  "info": {
    "name": "Okta Forgot Password (One Time Code)",
    "_postman_id": "4926e677-056a-4108-8ef6-a717a24cfbb6",
    "description": "Forgot password (one time code).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Forgot",
      "item": [
        {
          "id": "566dfc06-be0a-4fc5-91bc-72b423d94d83",
          "name": "postUsersUserCredentialsForgotPassword",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId/credentials/forgot_password"
              ],
              "query": [
                {
                  "key": "sendEmail",
                  "value": "%7B%7D",
                  "disabled": false
                }
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
            "description": "Forgot password (one time code)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c65c050-3127-4a10-9d5f-7afc4f4244c8"
            }
          ]
        }
      ]
    }
  ]
}