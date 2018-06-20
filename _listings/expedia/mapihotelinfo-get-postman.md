{
  "info": {
    "name": "Expedia Info",
    "_postman_id": "491e7dd9-dfd2-4446-b084-3be311dc1ae9",
    "description": "Hotel Information",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "4648ee61-9e87-461f-b1f1-1ff075a751a8",
          "name": "hotels-info",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/info?hotelId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Hotel Information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d630a521-25dd-4bac-afc0-40b94f8d3308"
            }
          ]
        }
      ]
    }
  ]
}