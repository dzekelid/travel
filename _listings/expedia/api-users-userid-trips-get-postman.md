{
  "info": {
    "name": "Expedia (Internal Only)",
    "_postman_id": "57cccf5e-7a17-4045-b716-c823f375e1e9",
    "description": "(Internal Only) Returns array of trips for passed userId",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "34836e48-1439-4d20-bac9-ccb264c7623c",
          "name": "trips-by-user-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apim.expedia.com",
              "path": [
                "x",
                "api/users/:userId/trips"
              ],
              "variable": [
                {
                  "id": "userId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "(Internal Only) Returns array of trips for passed userId"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d7a7904-47ba-45dd-be91-4b358480a138"
            }
          ]
        }
      ]
    }
  ]
}