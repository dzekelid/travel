{
  "info": {
    "name": "Expedia Get Offers",
    "_postman_id": "cb5c385d-0ea9-4ad5-8fbb-92dd9daaba4b",
    "description": "Mobile API Hotels Offers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "0b10a934-200e-4216-914a-280b8bbbddbb",
          "name": "hotels-offers",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/offers/v3?checkInDate=%7B%7D&checkOutDate=%7B%7D&hotelId=%7B%7D&priceType=%7B%7D&room=%7B%7D&room1=%7B%7D&sourceType=%7B%7D&useCacheForAirAttach=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Hotels Offers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bde791be-cf4c-43e6-8060-c89750b21bfa"
            }
          ]
        }
      ]
    }
  ]
}