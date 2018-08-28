swagger: "2.0"
x-collection-name: Amadeus
x-complete: 1
info:
  title: Amadeus
  description: amadeus-api-is-a-toolkit-designed-for-travel-agencies-who-want-to-develop-their-own-travel-products-rather-than-using-offtheshelf-solutions--with-this-tool-you-can-build-your-very-own-customised-applications-that-link-in-a-stable-and-secure-dialogue-with-our-global-distribution-system-gds-
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
  /airports/autocomplete:
    get:
      summary: Get Airports Autocomplete
      description: "Using the term parameter and given the start of any word in an
        airport's official name, a city name, or the start of an IATA code, this API
        provides the full name and IATA location code of the city or airport, for
        use in flight searches. Only major cities and civilian airports with several
        commercial flights per week are included by default. The response provides
        up to 20 possible matches, sorted by importance, in a JQuery UI Autocomplete
        compatible format. This sample implementation using JQuery UI may help. This
        API uses data from the OpenTravelData project.\n \nBy only using the country
        parameter, this API is also able to find all the IATA location codes associated
        with a country. Both term and country parameters can be used together to filter
        the results accordingly.          \n\nThe value returned is the IATA location
        code. The label returned is always in UTF-8 format, with the airport official
        name (which is often in the native language), in the format of English City
        Name (if not already included in the airport name)."
      operationId: getAirportsAutocomplete
      x-api-path-slug: airportsautocomplete-get
      parameters:
      - in: query
        name: all_airports
        description: Boolean to include or not all airports, no matter their traffic
          rank
      - in: query
        name: country
        description: Identified a country based of a ISO 3166-1 alpha-2 code
      - in: query
        name: term
        description: Search keyword that should represent the start of a word in a
          city or airport name
      responses:
        200:
          description: OK
      tags:
      - Airlines
      - Airports
      - Autocomplete
  /airports/nearest-relevant:
    get:
      summary: Get Airports Nearest Relevant
      description: |-
        This service gives the most relevant airports in a radius of 500 km around the given coordinates. The relevance of an airport is computed by dividing the number of airport movements (take offs and landings) by the distance from the point. This causes the relevance of an airport to increase exponentially as you approach it.

        To minimize response time, all distances are computed as a great-circle distance from the provided coordinates to the airport coordinates, and thus do not take into account traffic conditions, international boundaries, mountains, water, or other elements that might make the a nearby airport hard to reach.

        Only civilian airports with at least several commercial flights per week are included in the results.

        The result is a list of airports sorted by decreasing relevance. It always contains the nearest airport with significant commercial traffic. You can freely download the point of reference information used by this API from the Open Travel Data project.
      operationId: getAirportsNearestRelevant
      x-api-path-slug: airportsnearestrelevant-get
      parameters:
      - in: query
        name: latitude
        description: Latitude location to be at the center of your search circle
      - in: query
        name: longitude
        description: Longitude location to be at the center of your search circle
      responses:
        200:
          description: OK
      tags:
      - Airlines
      - Airports
      - Nearest
      - Relevant