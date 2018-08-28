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