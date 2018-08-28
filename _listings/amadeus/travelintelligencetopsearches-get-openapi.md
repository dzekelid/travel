---
swagger: "2.0"
x-collection-name: Amadeus
x-complete: 0
info:
  title: Amadeus Get Travel Intelligence Top Searches
  description: "The Top Flight Search allows you to find number of estimated searches
    from an origin, optionally a destination, within a time period when travelers
    are performing the searches. \nThe search is based on queries performed from within
    a country (also refers to as market) and returns up to 50 results, ordered by
    popularity, showing number of searches for most searched destination with its
    previous year comparison. This search also shows patterns on how travelers are
    searching for flights, revealing where, when and for how long they???re planning
    to travel. See\nTrip Durations(How long are the trips planned for?) and\n Advance
    Search Period (How long before departures do travelers start searching for their
    trips?)\n\nThis estimated search is based on Amadeus' Travel Intelligence Engine,
    a high performance scalable cloud-based platform, born in the age of Big Data
    and purposely built for the industry bringing total flexibility and speed to business
    intelligence for travel. Please see amadeus.com/travelintelligence for more information."
  contact:
    name: Amadeus Innovation and Research
    url: https://sandbox.amadeus.com
  version: 1.0.0
host: api.sandbox.amadeus.com
basePath: /v1.2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /travel-intelligence/flight-traffic:
    get:
      summary: Get Travel Intelligence Flight Traffic
      description: "The Flight Traffic API lets you find the origin and destination
        traffic summary between two journey points over a specified period.\nThe search
        returns number of flights & travelers for each origin and destination, ordered
        by popularity, for each month specified within the search period. This search
        can help you answer questions like \"Where are people from Los Angeles traveling
        to between January and April of 2015?\" or \"Which is the most popular month
        for New Yorkers to travel last year?\". \nThis search is based on Amadeus'
        Travel Intelligence Engine, a high performance scalable cloud-based platform,
        born in the age of Big Data and purposely built for the industry bringing
        total flexibility and speed to business intelligence for travel. Please see
        amadeus.com/travelintelligence for more information."
      operationId: getTravelIntelligenceFlightTraffic
      x-api-path-slug: travelintelligenceflighttraffic-get
      parameters:
      - in: query
        name: destination
        description: IATA code of the city to which the traveler is going
      - in: query
        name: number_of_results_per_period
        description: The maximum number of destinations to return for each period
      - in: query
        name: origin
        description: IATA code of the city from which the traveler will depart
      - in: query
        name: period
        description: Range of periods for which flight traffic information is required
      responses:
        200:
          description: OK
      tags:
      - Airlines
      - Travel
      - Intelligence
      - Flight
      - Traffic
  /travel-intelligence/top-destinations:
    get:
      summary: Get Travel Intelligence Top Destinations
      description: |-
        The Top Flight Destinations API lets you find the most popular flight destinations from an origin during a period. This can help you answer questions like "Where are most people from Paris going to during the month of September?" The API is based on estimated flight traffic summary data from two journey points over a specific period. It returns up to 50 results, ordered by popularity, showing number of travelers as well as number of flights.

        This estimated search is based on Amadeus' Travel Intelligence Engine, a high performance scalable cloud-based platform, born in the age of Big Data and purposely built for the industry bringing total flexibility and speed to business intelligence for travel. Please see amadeus.com/travelintelligence for more information.
      operationId: getTravelIntelligenceTopDestinations
      x-api-path-slug: travelintelligencetopdestinations-get
      parameters:
      - in: query
        name: number_of_results
        description: The maximum number of destinations to return in the results set
      - in: query
        name: origin
        description: IATA code of the city from which the traveler will depart
      - in: query
        name: period
        description: Period, in month of the year (YYYY-MM), when consumers are traveling
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Intelligence
      - Top
      - Destinations
  /travel-intelligence/top-searches:
    get:
      summary: Get Travel Intelligence Top Searches
      description: "The Top Flight Search allows you to find number of estimated searches
        from an origin, optionally a destination, within a time period when travelers
        are performing the searches. \nThe search is based on queries performed from
        within a country (also refers to as market) and returns up to 50 results,
        ordered by popularity, showing number of searches for most searched destination
        with its previous year comparison. This search also shows patterns on how
        travelers are searching for flights, revealing where, when and for how long
        they???re planning to travel. See\nTrip Durations(How long are the trips planned
        for?) and\n Advance Search Period (How long before departures do travelers
        start searching for their trips?)\n\nThis estimated search is based on Amadeus'
        Travel Intelligence Engine, a high performance scalable cloud-based platform,
        born in the age of Big Data and purposely built for the industry bringing
        total flexibility and speed to business intelligence for travel. Please see
        amadeus.com/travelintelligence for more information."
      operationId: getTravelIntelligenceTopSearches
      x-api-path-slug: travelintelligencetopsearches-get
      parameters:
      - in: query
        name: country
        description: 2-letter IATA country code of the country where the search queries
          originates from
      - in: query
        name: destination
        description: IATA code of the city to which the traveler is going
      - in: query
        name: number_of_results
        description: The maximum number of destinations to return in the results set
      - in: query
        name: origin
        description: IATA code of the city from which the traveler will depart
      - in: query
        name: period
        description: Period of date (month or year) when consumers are searching to
          travel
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Intelligence
      - Top
      - Searches
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