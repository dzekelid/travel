{
  "info": {
    "name": "Expedia Product",
    "_postman_id": "3ae5b6ba-c136-4bc5-9a2a-94d8e5f82ea3",
    "description": "Hotel Product",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "89d897d4-7f3a-41d8-b963-ccb21374af89",
          "name": "hotels-product",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/product?opaqueProduct=%7B%7D&productKey=%7B%7D&roomOccupants[0].childGuestAge=%7B%7D&roomOccupants[0].numberOfAdultGuests=%7B%7D&sourceType=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Hotel Product"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bda62fa9-8101-43a8-aa90-21d5fe770ff1"
            }
          ]
        }
      ]
    }
  ]
}