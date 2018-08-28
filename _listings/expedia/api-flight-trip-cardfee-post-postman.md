{
  "info": {
    "name": "Expedia",
    "_postman_id": "cb805db1-68ed-4b65-a1b1-f5ef5bd0b91e",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "73d29e89-8cae-4538-ba92-1d3ec72a6bb7",
          "name": "flights-trip-fee",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/trip/cardFee",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "clientId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Client Id"
                },
                {
                  "key": "creditCardId",
                  "value": "{}",
                  "disabled": false,
                  "description": "This is a string that identifies the credit card that will be used to pay for the trip"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The id of the trip to get the credit card fee for"
                }
              ]
            },
            "description": "This api provides an accurate credit card fee that a user would have to pay when booking a trip"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03173102-1a7e-4d91-ab72-36cfe9ba70b0"
            }
          ]
        }
      ]
    }
  ]
}