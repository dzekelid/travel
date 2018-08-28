---
swagger: "2.0"
x-collection-name: Amadeus
x-complete: 0
info:
  title: Amadeus Get Travel Record Record Locator
  description: |-
    Note: This API requires the use of HTTPS

    This service retrieves a travel record (also sometimes referred to as a PNR) for a given journey when provided with Record Locator to identify a travel record, along with the last name of any traveler who is marked as a passenger on this record.

    The API provides detailed information on a given record, including any air, car, hotel or rail reservations, as well as passenger details, and contact frequent traveler information for each passenger when available. You can use this to provide a wide variety of pre-trip or in-trip services.

    Note that this API transmits sensitive personal data about a traveler's journey. We work hard to ensure that we comply with all the legal requirements this entails, and as an application owner, you need to do so too - we don't want you to get in trouble! This paragraph, or anything else in our documentation, does not constitute legal advice, it's just to give you an idea of some of the potential issues that you may encounter. Please check your legal obligations regarding the use of this data before implementing this API

    In most countries, the data in the returned travel record is considered to be the property of the traveler. In order to ensure that you are acting on behalf of the traveler, we require you to provide the traveler's last name in addition to the record locator when you make a call to this API. You should ensure that you have consent from the traveler before retrieving this record, in some countries this is a legal requirement - please respect this appropriately.

    Our data center is based in Europe, so there is a legal requirement that you to access this API over a secure connection. If you plan to store the information returned by this API, ensure you comply with storage requirements for European data, in addition to those of your local country. For example, there are strict requirements on the caching of retrieved travel records, so please ensure the cache control HTTP headers in the response are respected.
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
        they\u2019re planning to travel. See\nTrip Durations(How long are the trips
        planned for?) and\n Advance Search Period (How long before departures do travelers
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
  /travel-record/{record_locator}:
    get:
      summary: Get Travel Record Record Locator
      description: |-
        Note: This API requires the use of HTTPS

        This service retrieves a travel record (also sometimes referred to as a PNR) for a given journey when provided with Record Locator to identify a travel record, along with the last name of any traveler who is marked as a passenger on this record.

        The API provides detailed information on a given record, including any air, car, hotel or rail reservations, as well as passenger details, and contact frequent traveler information for each passenger when available. You can use this to provide a wide variety of pre-trip or in-trip services.

        Note that this API transmits sensitive personal data about a traveler's journey. We work hard to ensure that we comply with all the legal requirements this entails, and as an application owner, you need to do so too - we don't want you to get in trouble! This paragraph, or anything else in our documentation, does not constitute legal advice, it's just to give you an idea of some of the potential issues that you may encounter. Please check your legal obligations regarding the use of this data before implementing this API

        In most countries, the data in the returned travel record is considered to be the property of the traveler. In order to ensure that you are acting on behalf of the traveler, we require you to provide the traveler's last name in addition to the record locator when you make a call to this API. You should ensure that you have consent from the traveler before retrieving this record, in some countries this is a legal requirement - please respect this appropriately.

        Our data center is based in Europe, so there is a legal requirement that you to access this API over a secure connection. If you plan to store the information returned by this API, ensure you comply with storage requirements for European data, in addition to those of your local country. For example, there are strict requirements on the caching of retrieved travel records, so please ensure the cache control HTTP headers in the response are respected.
      operationId: getTravelRecordRecordLocator
      x-api-path-slug: travelrecordrecord-locator-get
      parameters:
      - in: query
        name: env
        description: Indicates the Amadeus system from which this record should be
          retrieved
      - in: query
        name: last_name
        description: The last name of any traveler in this record, as written on their
          identification used for travel
      - in: path
        name: record_locator
        description: The Amadeus identifier of the given travel record
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Record
      - Record
      - Locator
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