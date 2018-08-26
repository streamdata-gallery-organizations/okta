{
  "info": {
    "name": "Okta Reset Factors",
    "_postman_id": "b4718cfe-7282-4351-943a-4f2b16e3922f",
    "description": "Reset factors.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Reset",
      "item": [
        {
          "id": "5dce4a64-0a75-429c-80ad-3f24009699da",
          "name": "postUsersUserLifecycleResetFactors",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId/lifecycle/reset_factors"
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
            "description": "Reset factors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd395f1a-db61-45a3-8f65-6c39ff857e0f"
            }
          ]
        }
      ]
    }
  ]
}