---
name: Expedia
x-slug: expedia
description: Expedia Affiliate Network is the B2B partnership brand of Expedia, Inc.
  Our technology powers the hotel offering of thousands of partners around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
x-kinRank: "9"
x-alexaRank: "197733"
tags: Travel
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apis.md
specificationVersion: "0.14"
apis:
- name: Expedia Search
  x-api-slug: expedia
  description: Mobile API Flights
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/search
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightsearch-get-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Flights Create Trip Operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/trip/create
  tags: Travel,Airports,Airplanes,Trips,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflighttripcreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflighttripcreate-post-openapi.md
- name: Expedia Get the credit card fee for a trip
  x-api-slug: expedia
  description: This api provides an accurate credit card fee that a user would have
    to pay when booking a trip.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/trip/cardFee
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflighttripcardfee-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflighttripcardfee-post-openapi.md
- name: Expedia Details
  x-api-slug: expedia
  description: Mobile API Flight Details Operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/details
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightdetails-get-openapi.md
- name: Expedia Flight Image
  x-api-slug: expedia
  description: Mobile API Flight Image Operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/image
  tags: Travel,Airports,Airplanes,Images,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightimage-get-openapi.md
- name: Expedia Mobile Image
  x-api-slug: expedia
  description: Mobile API Flight Mobile Image Operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/mobile/image
  tags: Travel,Airports,Airplanes,Images,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimobileimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimobileimage-get-openapi.md
- name: Expedia Airport Dropdown
  x-api-slug: expedia
  description: Mobile API Flight Airport Dropdown Operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/airportDropDown
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightairportdropdown-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightairportdropdown-get-openapi.md
- name: Expedia Mobile Flight Checkout
  x-api-slug: expedia
  description: Checkout a previously created flight trip, requiring payment fields,
    the trip id, and the passenger fields
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/checkout
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightcheckout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightcheckout-post-openapi.md
- name: Expedia Create a trip for partner
  x-api-slug: expedia
  description: Creates a flight trip, passing a product key and all required fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/flight/trip/V2/create
  tags: Travel,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapiflighttripv2create-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapiflighttripv2create-post-openapi.md
- name: Expedia Fare Rules for the trip
  x-api-slug: expedia
  description: Air Fare Rule information of the trip created
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/fareRules/{tripId}
  tags: Travel,Airports,Airplanes,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightfarerulestripid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiflightfarerulestripid-get-openapi.md
- name: Expedia Search
  x-api-slug: expedia
  description: |-
    Mobile API Hotels Search

    There are multiple successful responses for this operation.
    See the examples below for more information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/search
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelsearch-get-openapi.md
- name: Expedia Get Offers
  x-api-slug: expedia
  description: Mobile API Hotels Offers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/offers
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteloffers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteloffers-get-openapi.md
- name: Expedia Get Offers
  x-api-slug: expedia
  description: Mobile API Hotels Offers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/offers/v3
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteloffersv3-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteloffersv3-get-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Hotels Create Trip
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/create
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcreate-post-openapi.md
- name: Expedia Checkout
  x-api-slug: expedia
  description: Mobile API Hotels Checkout
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/checkout
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcheckout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcheckout-post-openapi.md
- name: Expedia Hotel Checkout With JSON Request Body
  x-api-slug: expedia
  description: Mobile API Hotel Checkout V2
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/V2/checkout
  tags: Travel,Hotels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripv2checkout-post-openapi.md
- name: Expedia Get Required Checkout Fields
  x-api-slug: expedia
  description: Service that returns the fields that are required or optional for a
    given point of sale.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/checkoutfields
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcheckoutfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcheckoutfields-get-openapi.md
- name: Expedia Cancel Enquiry
  x-api-slug: expedia
  description: Cancel Enquiry for hotel, pass in itinerary id, email address of trip
    owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/cancelEnquiry
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcancelenquiry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcancelenquiry-get-openapi.md
- name: Expedia Cancel Enquiry
  x-api-slug: expedia
  description: Cancel Enquiry for hotel, pass in itinerary id, email address of trip
    owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/V2/cancelEnquiry
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripv2cancelenquiry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripv2cancelenquiry-get-openapi.md
- name: Expedia Product
  x-api-slug: expedia
  description: Hotel Product
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/product
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelproduct-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelproduct-get-openapi.md
- name: Expedia Info
  x-api-slug: expedia
  description: Hotel Information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/info
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelinfo-get-openapi.md
- name: Expedia Cancel Trip
  x-api-slug: expedia
  description: Hotel Trip Cancellation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/trip/cancel
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihoteltripcancel-post-openapi.md
- name: Expedia Cancel Room
  x-api-slug: expedia
  description: Hotel Room Cancellation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/rooms/cancel
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelroomscancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelroomscancel-post-openapi.md
- name: Expedia Points Conversion
  x-api-slug: expedia
  description: |-
    Converts from a given currency amount to the equivalent in rewards points.
    [Note: Works only if the User is signed-in and is the owner of the trip.]
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/trip/calculatePoints
  tags: Travel,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapitripcalculatepoints-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapitripcalculatepoints-post-openapi.md
- name: Expedia Get Packages
  x-api-slug: expedia
  description: Gets packages and supports changed flights and hotels for flexible
    shopping.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///getpackages/v1
  tags: Travel,Packages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/getpackagesv1-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/getpackagesv1-get-openapi.md
- name: Expedia Get Package Offers
  x-api-slug: expedia
  description: Mobile API Packages
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/packages/hotelOffers
  tags: Travel,Packages,Offers,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackageshoteloffers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackageshoteloffers-get-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Packages Create Trip operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/packages/createTrip
  tags: Travel,Packages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackagescreatetrip-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackagescreatetrip-post-openapi.md
- name: Expedia Checkout
  x-api-slug: expedia
  description: Mobile API Packages Checkout
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/packages/checkout
  tags: Travel,Packages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackagescheckout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apipackagescheckout-post-openapi.md
- name: Expedia Apply Coupon
  x-api-slug: expedia
  description: Mobile API Packages Apply Coupon
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/m/trip/coupon
  tags: Travel,Airports,Airplanes,Coupons,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimtripcoupon-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimtripcoupon-post-openapi.md
- name: Expedia Remove Coupon
  x-api-slug: expedia
  description: Mobile API Packages Remove Coupon
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/m/trip/remove/coupon
  tags: Travel,Airports,Airplanes,Coupons,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimtripremovecoupon-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apimtripremovecoupon-post-openapi.md
- name: Expedia Get Trips
  x-api-slug: expedia
  description: Mobile API Trips
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/trips
  tags: Travel,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitrips-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitrips-get-openapi.md
- name: Expedia Trips by tripId
  x-api-slug: expedia
  description: Mobile API Trips
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/trips/{tripId}
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitripstripid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitripstripid-get-openapi.md
- name: Expedia Update Trip Name and Description
  x-api-slug: expedia
  description: Mobile API Trips update trip name and description operation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/trips/{tripId}/updateTripNameDescription
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitripstripidupdatetripnamedescription-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apitripstripidupdatetripnamedescription-post-openapi.md
- name: Expedia (Internal Only)
  x-api-slug: expedia
  description: (Internal Only) Retrieve trip (tripId) for given customer (userId)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/users/{userId}/trips/{tripId}
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersuseridtripstripid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersuseridtripstripid-get-openapi.md
- name: Expedia (Internal Only)
  x-api-slug: expedia
  description: (Internal Only) Returns array of trips for passed userId
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/users/{userId}/trips
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersuseridtrips-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersuseridtrips-get-openapi.md
- name: Expedia Get the credit card fee for a trip
  x-api-slug: expedia
  description: This api provides an accurate credit card fee that a user would have
    to pay when booking a trip.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/rails/trip/cardFee
  tags: Travel,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapirailstripcardfee-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapirailstripcardfee-post-openapi.md
- name: Expedia Rails Checkout With JSON Request Body
  x-api-slug: expedia
  description: Mobile API Rails Checkout
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/rails/trip/checkout
  tags: Travel,Trains,Rails
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapirailstripcheckout-post-openapi.md
- name: Expedia User Sign-In
  x-api-slug: expedia
  description: Mobile API User Sign-In
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/sign-in
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersignin-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusersignin-post-openapi.md
- name: Expedia Profile
  x-api-slug: expedia
  description: Mobile API User Profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/profile
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserprofile-get-openapi.md
- name: Expedia Create User
  x-api-slug: expedia
  description: Mobile API User Create
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/create
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusercreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiusercreate-post-openapi.md
- name: Expedia Update
  x-api-slug: expedia
  description: Mobile API User Update Traveler
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/update-traveler
  tags: Travel,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserupdatetraveler-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserupdatetraveler-post-openapi.md
- name: Expedia Associate User To Trip
  x-api-slug: expedia
  description: Mobile API User Associate To Trip
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/associateUserToTrip
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserassociateusertotrip-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/apiuserassociateusertotrip-post-openapi.md
- name: Expedia Search
  x-api-slug: expedia
  description: Mobile API Cars
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/search/airport
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearchairport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearchairport-get-openapi.md
- name: Expedia Search
  x-api-slug: expedia
  description: Mobile API Cars
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/search/location
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearchlocation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearchlocation-get-openapi.md
- name: Expedia Search
  x-api-slug: expedia
  description: Mobile API Cars
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/search
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarssearch-get-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Cars Create Trip
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/trip/create
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcreate-post-openapi.md
- name: Expedia Checkout
  x-api-slug: expedia
  description: Mobile API Cars Checkout
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/trip/checkout
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcheckout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcheckout-post-openapi.md
- name: Expedia Cancel Trip
  x-api-slug: expedia
  description: car Trip Cancellation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/cars/trip/cancel
  tags: Travel,Cars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapicarstripcancel-post-openapi.md
- name: Expedia Search
  x-api-slug: expedia
  description: LX Shop Search
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///lx/api/search
  tags: Travel,Shop
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/lxapisearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/lxapisearch-get-openapi.md
- name: Expedia Infosite/Details
  x-api-slug: expedia
  description: Lx Details Search
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///lx/api/activity
  tags: Travel,Activities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/lxapiactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/lxapiactivity-get-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Lx Create Trip
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/lx/trip/create
  tags: Travel,Trips
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapilxtripcreate-post-openapi.md
- name: Expedia Checkout
  x-api-slug: expedia
  description: Mobile API Lx Checkout
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/lx/trip/checkout
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapilxtripcheckout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapilxtripcheckout-post-openapi.md
- name: Expedia LPAS Search
  x-api-slug: expedia
  description: Mobile API Hotel Search using LPAS
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/hotel/search/v3
  tags: Travel,Hotels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelsearchv3-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/mapihotelsearchv3-get-openapi.md
- name: Expedia
  x-api-slug: expedia
  description: Expedia is the leader in travel and technology and is the worlds largest
    travel company. The EAN Developer Hub gives developers FREE access to our highly
    flexible APIs that power cutting-edge websites, mobile apps, and much more. Some
    of the best travel applications on the market are powered by the EAN API. Learn
    more reasons to partner with EAN by taking a look at our brochure and watching
    our video. The world of travel awaits you!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/195-expedia.jpg
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x/
  tags: Travel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/travel/master/_listings/expedia/openapi.md
x-common:
- type: x-base
  url: http://api.ean.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/expedia
- type: x-crunchbase
  url: https://crunchbase.com/organization/ean-upc-codes-com
- type: x-documentation
  url: https://www.expedia.com/static/mobile/swaggerui/
- type: x-email
  url: support@ean.com
- type: x-github
  url: https://github.com/Expedia
- type: x-swagger--original
  url: https://www.expedia.com/static/mobile/swaggerui/swagger.json
- type: x-twitter
  url: https://twitter.com/ExpediaEAN
- type: x-website
  url: http://developer.ean.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---