{
  "info": {
    "name": "Expedia Cancel Enquiry",
    "_postman_id": "0f521330-6d8d-4e46-9b53-2144eff0b099",
    "description": "Cancel Enquiry for hotel, pass in itinerary id, email address of trip owner.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "13e105a0-c11c-48dc-a682-fe8215c1cefb",
          "name": "hotels-cancel-enquiry",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/cancelEnquiry?emailAddress=%7B%7D&itineraryId=%7B%7D",
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
              "id": "124a7779-70ec-475d-9baf-eb28883f9560"
            }
          ]
        }
      ]
    }
  ]
}