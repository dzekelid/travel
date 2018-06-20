---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Flight Image
  description: Mobile API Flight Image Operation
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/search:
    get:
      summary: Search
      description: Mobile API Flights
      operationId: flights-search
      x-api-path-slug: apiflightsearch-get
      parameters:
      - in: query
        name: arrivalAirport
        description: The three letter airport code to where the customer is going
      - in: query
        name: childTravelerAge
        description: childTravelerAge represents the age of a single child traveler
      - in: query
        name: correlationId
        description: Optional parameter to define a correlation between a hotel search
          and a flight search
      - in: query
        name: departureAirport
        description: The three letter airport code for where the customer is leaving
          from
      - in: query
        name: departureDate
        description: Date the customer wants to leave for their flight on, in ISO
          format
      - in: query
        name: featureOverride
        description: Optional field to specify a comma separated list of feature toggling
          flag names, use _ (underscore) ahead of flag name to disable feature ex,
          Flex,FlightSearchCacheGet,_FlightSearchCachePut
      - in: query
        name: infantSeatingInLap
        description: Set to true if infant(s) are without a reserved seat (in an adults
          lap)
      - in: query
        name: lccAndMerchantFareCheckoutAllowed
        description: flag to indicate whether lcc and merchant fares should be returned
          in search response
      - in: query
        name: maxOfferCount
        description: Maximum number of offers to return
      - in: query
        name: nonStopFlight
        description: 'Set to true to return only non stop flights in the search response '
      - in: query
        name: numberOfAdultTravelers
        description: 'Number of Adult Travelers (Default: 1)'
      - in: query
        name: prettyPrint
        description: Controls JSON response formatting
      - in: query
        name: returnDate
        description: Date the customer wants to return on
      - in: query
        name: showRefundableFlight
        description: 'Set to true to return only refundable(Free cancellation available)
          flights in the search response '
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
  /api/flight/trip/create:
    post:
      summary: Create A Trip
      description: Mobile API Flights Create Trip Operation
      operationId: flights-create-trip
      x-api-path-slug: apiflighttripcreate-post
      parameters:
      - in: formData
        name: fareFamilyCode
      - in: formData
        name: fareFamilyTotalPrice
      - in: formData
        name: mobileShoppingKey
        description: The mobile shopping key we are going to create a trip for
      - in: formData
        name: productKey
        description: The product key, obtained from /api/flight/search, we are going
          to create a trip for
      - in: formData
        name: qualifyAirAttach
        description: Whether to return a qualified air attach product for this trip
      - in: formData
        name: tripTitle
        description: The name of this itinerary as it will appear to customer service
          and in the itinerary list
      - in: formData
        name: withInsurance
        description: Whether to return the available insurance options for this trip
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Trips
      - Airlines
  /api/flight/trip/cardFee:
    post:
      summary: Get the credit card fee for a trip
      description: This api provides an accurate credit card fee that a user would
        have to pay when booking a trip.
      operationId: flights-trip-fee
      x-api-path-slug: apiflighttripcardfee-post
      parameters:
      - in: formData
        name: clientId
        description: Client Id
      - in: formData
        name: creditCardId
        description: This is a string that identifies the credit card that will be
          used to pay for the trip
      - in: formData
        name: tripId
        description: The id of the trip to get the credit card fee for
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
  /api/flight/details:
    get:
      summary: Details
      description: Mobile API Flight Details Operation
      operationId: flights-details
      x-api-path-slug: apiflightdetails-get
      parameters:
      - in: query
        name: arrivalAirport
        description: The three letter airport code for where the customer is going
      - in: query
        name: childTravelerAge
        description: childTravelerAge represents the age of a single child traveler
      - in: query
        name: departureAirport
        description: The three letter airport code for where the customer is leaving
          from
      - in: query
        name: departureDate
        description: Date the customer wants to leave for their flight on, in ISO
          format
      - in: query
        name: infantSeatingInLap
        description: Set to true if infant(s) are without a reserved seat (in an adults
          lap)
      - in: query
        name: numberOfAdultTravelers
        description: 'Number of Adult Travelers (Default: 1)'
      - in: query
        name: productKey
        description: A productKey, obtained from a call to flight search, within the
          past 20 minutes
      - in: query
        name: returnDate
        description: Date the customer wants to return on
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
  /api/flight/image:
    get:
      summary: Flight Image
      description: Mobile API Flight Image Operation
      operationId: flights-image
      x-api-path-slug: apiflightimage-get
      parameters:
      - in: query
        name: destinationCode
        description: The three letter airport code or metro code of the destination
      - in: query
        name: imageHeight
        description: Requested height of the image
      - in: query
        name: imageWidth
        description: Requested width of the image
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Images
      - Airlines
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---