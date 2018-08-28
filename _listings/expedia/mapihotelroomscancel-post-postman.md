{
  "info": {
    "name": "Expedia Cancel Room",
    "_postman_id": "9c3624e8-58b5-4eec-8b31-47ff94865e75",
    "description": "Hotel Room Cancellation",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "0ab90115-4888-47b4-9140-4e4d965c04c4",
          "name": "hotels-room-cancel",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/rooms/cancel",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "orderLineGUIDs",
                  "value": "{}",
                  "disabled": false,
                  "description": "The list of order line guids"
                },
                {
                  "key": "orderNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "The order number ( returned by OMS ) associated with the trip"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The trip ID ( returned while checkout ) associated with the trip"
                }
              ]
            },
            "description": "Hotel Room Cancellation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b157720-b5e0-4ccd-8829-ed4bb856c3dc"
            }
          ]
        }
      ]
    }
  ]
}