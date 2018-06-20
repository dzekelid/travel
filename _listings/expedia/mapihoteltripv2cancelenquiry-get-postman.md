{
  "info": {
    "name": "Expedia Cancel Enquiry",
    "_postman_id": "237c6c76-e0fb-4047-a4cd-f4d3ccd6e688",
    "description": "Cancel Enquiry for hotel, pass in itinerary id, email address of trip owner.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "f6beda71-fbd9-4e64-adba-5d4645a04cf6",
          "name": "hotels-cancel-enquiry",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/V2/cancelEnquiry?emailAddress=%7B%7D&itineraryId=%7B%7D&orderLineGUIDs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel Enquiry for hotel, pass in itinerary id, email address of trip owner"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c7f413a-f461-4ad0-b621-3bbe3fc3e3aa"
            }
          ]
        }
      ]
    }
  ]
}