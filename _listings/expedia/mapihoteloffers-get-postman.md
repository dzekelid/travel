{
  "info": {
    "name": "Expedia Get Offers",
    "_postman_id": "a3de6362-54e1-4f52-bd50-2d11bb1c953f",
    "description": "Mobile API Hotels Offers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "f4664b1e-1a2b-4b92-8124-a439d3793b33",
          "name": "hotels-offers",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/offers?checkInDate=%7B%7D&checkOutDate=%7B%7D&hotelId=%7B%7D&priceType=%7B%7D&room=%7B%7D&room1=%7B%7D&sourceType=%7B%7D&useCacheForAirAttach=%7B%7D",
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
              "id": "aa9cc653-d789-4f39-bcad-294b516a862a"
            }
          ]
        }
      ]
    }
  ]
}