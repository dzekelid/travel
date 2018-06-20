{
  "info": {
    "name": "Expedia",
    "_postman_id": "493b6a3a-1c12-44e9-80fc-cc52d12080dc",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "84a16592-b1b7-496a-8f4f-cecf9568ea95",
          "name": "flights-fareRules",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apim.expedia.com",
              "path": [
                "x",
                "api/flight/fareRules/:tripId"
              ],
              "variable": [
                {
                  "id": "tripId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Air Fare Rule information of the trip created"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "161245a5-b33c-435d-8d39-80e78068c0ab"
            }
          ]
        }
      ]
    }
  ]
}