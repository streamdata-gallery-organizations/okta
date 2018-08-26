{
  "info": {
    "name": "Okta Get Assigned App Links",
    "_postman_id": "8fa8b005-237b-4bcd-a9ca-097e3df7585a",
    "description": "Get assigned app links.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Assigned",
      "item": [
        {
          "id": "52bf2dba-73bf-4411-b122-30ee968fb23a",
          "name": "getUsersUserApplinks",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "v1",
                "users/:userId/appLinks"
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
            "description": "Get assigned app links."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42590648-3dff-41f7-aa09-c6303265f34b"
            }
          ]
        }
      ]
    }
  ]
}