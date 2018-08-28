{
  "info": {
    "name": "Expedia Create A Trip",
    "_postman_id": "c67a4e4b-7668-4b10-85c1-469893f2b2d4",
    "description": "Mobile API Hotels Create Trip",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "a0ca8ad6-a3b7-4ce3-84d5-4065bf0a7582",
          "name": "hotels-create-trip",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/create",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "productKey",
                  "value": "{}",
                  "disabled": false,
                  "description": "The product key, obtained by calling /m/api/hotel/offers,  we are going to create a trip for"
                },
                {
                  "key": "qualifyAirAttach",
                  "value": "{}",
                  "disabled": false,
                  "description": "[Optional] Whether to return a qualified air attach product for this trip"
                },
                {
                  "key": "roomInfoFields[0].room",
                  "value": "{}",
                  "disabled": false,
                  "description": "A Comma Separated Value of #OfAdults, followed by children's ages for all children that are 18 and under"
                },
                {
                  "key": "tripTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": "[Optional] The name of this itinerary as it will appear to customer service and in the itinerary list"
                },
                {
                  "key": "withInsurance",
                  "value": "{}",
                  "disabled": false,
                  "description": "[Optional] Whether to return the available insurance options for this trip"
                }
              ]
            },
            "description": "Mobile API Hotels Create Trip"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e97964e5-613e-4d49-b0a1-005573efb2fc"
            }
          ]
        }
      ]
    }
  ]
}