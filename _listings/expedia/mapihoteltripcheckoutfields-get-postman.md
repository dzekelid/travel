{
  "info": {
    "name": "Expedia Get Required Checkout Fields",
    "_postman_id": "3f7d8bff-6ad4-42ac-968e-1705326b1684",
    "description": "Service that returns the fields that are required or optional for a given point of sale.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "75120466-42f4-4024-8d65-d3219238cb69",
          "name": "hotels-checkout-fields",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/checkoutfields",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service that returns the fields that are required or optional for a given point of sale"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85832a86-3beb-4d7d-90bb-9c9583e9a156"
            }
          ]
        }
      ]
    }
  ]
}