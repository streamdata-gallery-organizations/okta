---
swagger: "2.0"
x-collection-name: Okta
x-complete: 0
info:
  title: Okta Forgot Password (One Time Code)
  description: Forgot password (one time code).
  version: 1.0.0
host: example.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{userId}:
    get:
      summary: Get User
      description: Get user.
      operationId: getUsersUser
      x-api-path-slug: usersuserid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - User
    put:
      summary: Set Password
      description: Set password.
      operationId: putUsersUser
      x-api-path-slug: usersuserid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Password
  /users:
    get:
      summary: List Password Expired Users
      description: List password expired users.
      operationId: getUsers
      x-api-path-slug: users-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: filter
      - in: query
        name: limit
      responses:
        200:
          description: OK
      tags:
      - List
      - Password
      - Expired
      - Users
    post:
      summary: Create User without Credentials
      description: Create user without credentials.
      operationId: postUsers
      x-api-path-slug: users-post
      parameters:
      - in: header
        name: Accept
      - in: query
        name: activate
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - User
      - Without
      - Credentials
  /users/{userId}/lifecycle/reset_factors:
    post:
      summary: Reset Factors
      description: Reset factors.
      operationId: postUsersUserLifecycleResetFactors
      x-api-path-slug: usersuseridlifecyclereset-factors-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Reset
      - Factors
  /users/{userId}/lifecycle/suspend:
    post:
      summary: Suspend User
      description: Suspend user.
      operationId: postUsersUserLifecycleSuspend
      x-api-path-slug: usersuseridlifecyclesuspend-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Suspend
      - User
  /users/{userId}/credentials/forgot_password:
    post:
      summary: Forgot Password (One Time Code)
      description: Forgot password (one time code).
      operationId: postUsersUserCredentialsForgotPassword
      x-api-path-slug: usersuseridcredentialsforgot-password-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: sendEmail
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Forgot
      - Password
      - (One
      - Time
      - Code)
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---