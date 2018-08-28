{
  "info": {
    "name": "Expedia",
    "_postman_id": "8e3e94d1-6cc9-41ab-b2db-35faeeecbacd",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "48274853-5f1a-411d-92a4-96ba61923240",
          "name": "flights-checkout",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/flight/trip/V2/create",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "childTravelerAge[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": "childTravelerAge represents the age of a single child traveler"
                },
                {
                  "key": "infantSeatingInLap",
                  "value": "{}",
                  "disabled": false,
                  "description": "Set to true if infant(s) are without a reserved seat (in an adult's lap)"
                },
                {
                  "key": "numberOfAdultTravelers",
                  "value": "{}",
                  "disabled": false,
                  "description": "Number of Adult Travelers (Default: 1)"
                },
                {
                  "key": "productKey",
                  "value": "{}",
                  "disabled": false,
                  "description": "The product key we are going to create a trip for"
                },
                {
                  "key": "tripTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": "The name of this itinerary as it will appear to customer service and in the itinerary list"
                },
                {
                  "key": "withInsurance",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to return the available insurance options for this trip"
                }
              ]
            },
            "description": "Creates a flight trip, passing a product key and all required fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f415a51-7359-421f-b6b1-8ae0e8dea4ce"
            }
          ]
        }
      ]
    }
  ]
}