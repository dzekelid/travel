{
  "info": {
    "name": "Expedia Get the credit card fee for a trip",
    "_postman_id": "1a86a02e-fd3a-4247-8366-f9a563ae0ab1",
    "description": "This api provides an accurate credit card fee that a user would have to pay when booking a trip.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "283e1b8d-0fce-407a-a374-0716ca10c180",
          "name": "rails-trip-fee",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/rails/trip/cardFee",
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
                  "key": "tdoToken",
                  "value": "{}",
                  "disabled": false,
                  "description": "This is a string that identifies the ticket delivery option that will be used for the trip"
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
              "id": "2fad06e1-e0be-4d1f-85b3-41f7dc8eff31"
            }
          ]
        }
      ]
    }
  ]
}