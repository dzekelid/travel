{
  "info": {
    "name": "Expedia",
    "_postman_id": "04626faf-6cf1-4843-83ad-a360fe27f2b6",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "e5131d8c-1058-400a-bb75-a7468fa7124e",
          "name": "lx-details",
          "request": {
            "url": "http://apim.expedia.com/x/lx/api/activity?activityId=%7B%7D&endDate=%7B%7D&langid=%7B%7D&startDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lx Details Search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07145939-0000-4aa2-8a85-5bf2e3594f73"
            }
          ]
        }
      ]
    }
  ]
}