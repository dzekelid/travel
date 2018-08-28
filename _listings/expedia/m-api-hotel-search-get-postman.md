{
  "info": {
    "name": "Expedia Search",
    "_postman_id": "02192864-6c6d-4a20-b4b2-dcaf77add6cc",
    "description": "Mobile API Hotels Search\n\nThere are multiple successful responses for this operation.\nSee the examples below for more information.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "1e0e3ced-01ac-481a-84d4-ac980a3165f3",
          "name": "hotels-search",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/search?airAttachQualificationCode=%7B%7D&checkInDate=%7B%7D&checkOutDate=%7B%7D&city=%7B%7D&correlationId=%7B%7D&enableSponsoredListings=%7B%7D&filterAmenities=%7B%7D&filterHotelName=%7B%7D&filterInventoryType=%7B%7D&filterPrice=%7B%7D&filterPriceBuckets=%7B%7D&filterStarRatings=%7B%7D&filterUnavailable=%7B%7D&forceV2Search=%7B%7D&hgid=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&pageIndex=%7B%7D&regionId=%7B%7D&resultsPerPage=%7B%7D&returnOpaqueHotels=%7B%7D&room=%7B%7D&room1=%7B%7D&sortOrder=%7B%7D&sortOrderFilter=%7B%7D&sourceType=%7B%7D&tripId=%7B%7D&vipOnly=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Hotels Search\n\nThere are multiple successful responses for this operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4d0bcab-64ce-4d3a-b282-292a15e17e12"
            }
          ]
        }
      ]
    }
  ]
}