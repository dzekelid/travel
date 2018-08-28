{
  "info": {
    "name": "Expedia Cancel Trip",
    "_postman_id": "2bbed36a-b8c3-42bc-b27a-9248ffbe64e8",
    "description": "Hotel Trip Cancellation",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "d7260cdc-f322-4819-9b62-ba18a3d9dbb0",
          "name": "hotels-trip-cancel",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/cancel",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "emailAddress",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email address of the traveler"
                },
                {
                  "key": "itineraryId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Itinerary id of the trip to cancel"
                },
                {
                  "key": "sendConfirmationEmail",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email the traveler after cancellation or not"
                }
              ]
            },
            "description": "Hotel Trip Cancellation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5614938-880c-4606-a736-4254a12c97b6"
            }
          ]
        }
      ]
    }
  ]
}