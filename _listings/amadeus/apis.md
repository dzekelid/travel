---
name: Amadeus
x-slug: amadeus
description: Amadeus travel technology helps businesses connect to the global travel
  ecosystem, manage operations more effectively and serve travellers better than ever
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
x-kinRank: "8"
x-alexaRank: "4309"
tags: Travel
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/apis.md
specificationVersion: "0.14"
apis:
- name: Amadeus - Get Travel Intelligence Flight Traffic
  x-api-slug: travelintelligenceflighttraffic-get
  description: "The Flight Traffic API lets you find the origin and destination traffic
    summary between two journey points over a specified period.\nThe search returns
    number of flights & travelers for each origin and destination, ordered by popularity,
    for each month specified within the search period. This search can help you answer
    questions like \"Where are people from Los Angeles traveling to between January
    and April of 2015?\" or \"Which is the most popular month for New Yorkers to travel
    last year?\". \nThis search is based on Amadeus' Travel Intelligence Engine, a
    high performance scalable cloud-based platform, born in the age of Big Data and
    purposely built for the industry bringing total flexibility and speed to business
    intelligence for travel. Please see amadeus.com/travelintelligence for more information."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligenceflighttraffic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligenceflighttraffic-get-openapi.md
- name: Amadeus - Get Travel Intelligence Top Destinations
  x-api-slug: travelintelligencetopdestinations-get
  description: |-
    The Top Flight Destinations API lets you find the most popular flight destinations from an origin during a period. This can help you answer questions like "Where are most people from Paris going to during the month of September?" The API is based on estimated flight traffic summary data from two journey points over a specific period. It returns up to 50 results, ordered by popularity, showing number of travelers as well as number of flights.

    This estimated search is based on Amadeus' Travel Intelligence Engine, a high performance scalable cloud-based platform, born in the age of Big Data and purposely built for the industry bringing total flexibility and speed to business intelligence for travel. Please see amadeus.com/travelintelligence for more information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligencetopdestinations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligencetopdestinations-get-openapi.md
- name: Amadeus - Get Travel Intelligence Top Searches
  x-api-slug: travelintelligencetopsearches-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligencetopsearches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelintelligencetopsearches-get-openapi.md
- name: Amadeus - Get Travel Record Record Locator
  x-api-slug: travelrecordrecord-locator-get
  description: |-
    Note: This API requires the use of HTTPS

    This service retrieves a travel record (also sometimes referred to as a PNR) for a given journey when provided with Record Locator to identify a travel record, along with the last name of any traveler who is marked as a passenger on this record.

    The API provides detailed information on a given record, including any air, car, hotel or rail reservations, as well as passenger details, and contact frequent traveler information for each passenger when available. You can use this to provide a wide variety of pre-trip or in-trip services.

    Note that this API transmits sensitive personal data about a traveler's journey. We work hard to ensure that we comply with all the legal requirements this entails, and as an application owner, you need to do so too - we don't want you to get in trouble! This paragraph, or anything else in our documentation, does not constitute legal advice, it's just to give you an idea of some of the potential issues that you may encounter. Please check your legal obligations regarding the use of this data before implementing this API

    In most countries, the data in the returned travel record is considered to be the property of the traveler. In order to ensure that you are acting on behalf of the traveler, we require you to provide the traveler's last name in addition to the record locator when you make a call to this API. You should ensure that you have consent from the traveler before retrieving this record, in some countries this is a legal requirement - please respect this appropriately.

    Our data center is based in Europe, so there is a legal requirement that you to access this API over a secure connection. If you plan to store the information returned by this API, ensure you comply with storage requirements for European data, in addition to those of your local country. For example, there are strict requirements on the caching of retrieved travel records, so please ensure the cache control HTTP headers in the response are respected.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelrecordrecord-locator-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/travelrecordrecord-locator-get-openapi.md
- name: Amadeus - Get Airports Autocomplete
  x-api-slug: airportsautocomplete-get
  description: "Using the term parameter and given the start of any word in an airport's
    official name, a city name, or the start of an IATA code, this API provides the
    full name and IATA location code of the city or airport, for use in flight searches.
    Only major cities and civilian airports with several commercial flights per week
    are included by default. The response provides up to 20 possible matches, sorted
    by importance, in a JQuery UI Autocomplete compatible format. This sample implementation
    using JQuery UI may help. This API uses data from the OpenTravelData project.\n
    \nBy only using the country parameter, this API is also able to find all the IATA
    location codes associated with a country. Both term and country parameters can
    be used together to filter the results accordingly.          \n\nThe value returned
    is the IATA location code. The label returned is always in UTF-8 format, with
    the airport official name (which is often in the native language), in the format
    of English City Name (if not already included in the airport name)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/airportsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/airportsautocomplete-get-openapi.md
- name: Amadeus - Get Airports Nearest Relevant
  x-api-slug: airportsnearestrelevant-get
  description: |-
    This service gives the most relevant airports in a radius of 500 km around the given coordinates. The relevance of an airport is computed by dividing the number of airport movements (take offs and landings) by the distance from the point. This causes the relevance of an airport to increase exponentially as you approach it.

    To minimize response time, all distances are computed as a great-circle distance from the provided coordinates to the airport coordinates, and thus do not take into account traffic conditions, international boundaries, mountains, water, or other elements that might make the a nearby airport hard to reach.

    Only civilian airports with at least several commercial flights per week are included in the results.

    The result is a list of airports sorted by decreasing relevance. It always contains the nearest airport with significant commercial traffic. You can freely download the point of reference information used by this API from the Open Travel Data project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/airportsnearestrelevant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/amadeus/airportsnearestrelevant-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://amadeus.api.gallery.streamdata.io
- type: x-api-stack
  url: http://amadeus.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/amadeus
- type: x-documentation
  url: https://sandbox.amadeus.com/api-catalog
- type: x-github
  url: https://github.com/AmadeusITGroup
- type: x-privacy-policy
  url: http://www.amadeus.com/web/amadeus/en_1A-corporate/Amadeus-Home/Amadeus_IT_Group_SA-Legal-notices-2014/1319560218660-Page-AMAD_Detail_PopUp_Ppal?assetid=1319607040997&assettype=DataProtection_C
- type: x-sandbox
  url: https://sandbox.amadeus.com
- type: x-twitter
  url: https://twitter.com/amadeusinnov
- type: x-website
  url: https://amadeus.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---