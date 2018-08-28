{
  "info": {
    "name": "Expedia (Internal Only)",
    "_postman_id": "088ae26e-556f-49d2-ace3-2d84c1bc6d3f",
    "description": "(Internal Only) Retrieve trip (tripId) for given customer (userId)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "21f15af2-c265-4e94-ac4f-9fc799c9ccf1",
          "name": "trips-user-trips",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apim.expedia.com",
              "path": [
                "x",
                "api/users/:userId/trips/:tripId"
              ],
              "query": [
                {
                  "key": "currencyCode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "decimalPlaceCount",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "decorator",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "email",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "expectedAmount",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "useCache",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "tripId",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "(Internal Only) Retrieve trip (tripId) for given customer (userId)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20cb542f-5bfb-4383-830b-0632a8062437"
            }
          ]
        }
      ]
    }
  ]
}