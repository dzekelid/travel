{
  "info": {
    "name": "Expedia Points Conversion",
    "_postman_id": "79040c67-32cf-4f99-87ec-e4ca7fde727e",
    "description": "Converts from a given currency amount to the equivalent in rewards points.\n[Note: Works only if the User is signed-in and is the owner of the trip.]",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "b5b073fc-1c2c-42ab-b1f1-bde5bea5c664",
          "name": "hotels-trip-calculate",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/trip/calculatePoints",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "amount",
                  "value": "{}",
                  "disabled": false,
                  "description": "The amount the user would want to convert to points"
                },
                {
                  "key": "programName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The Rewards program name"
                },
                {
                  "key": "rateId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The rate id to use for this conversion"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The trip ID of an existing trip, from /api/packages/createTrip"
                }
              ]
            },
            "description": "Converts from a given currency amount to the equivalent in rewards points"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c164073-786c-4f94-b911-f149e4d0353b"
            }
          ]
        }
      ]
    }
  ]
}