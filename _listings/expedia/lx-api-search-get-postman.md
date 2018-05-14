{
  "info": {
    "name": "Expedia Search",
    "_postman_id": "f269a0a7-6fa4-4478-833c-1d1baf0fd31e",
    "description": "LX Shop Search",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "f8cf710c-4d57-49ab-a179-6b0e2a1f6356",
          "name": "lx-search",
          "request": {
            "url": "http://apim.expedia.com/x/lx/api/search?endDate=%7B%7D&langid=%7B%7D&location=%7B%7D&startDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "LX Shop Search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "008dc3cd-97c5-477d-b796-5ab0bc862b4c"
            }
          ]
        }
      ]
    }
  ]
}