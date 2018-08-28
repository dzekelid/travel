swagger: "2.0"
x-collection-name: Expedia
x-complete: 1
info:
  title: Expedia
  description: expedia-mobile-api-documentation--brfont-colorblue-note-in-case-of-authorization-exception-just-a-hrefstaticmobileswaggeruiusersigninusersigninafont
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
  /api/user/update-traveler:
    post:
      summary: Update
      description: Mobile API User Update Traveler
      operationId: update-traveler
      x-api-path-slug: apiuserupdatetraveler-post
      parameters:
      - in: formData
        name: birthDate
        description: TSA required field; passengers birth date
      - in: formData
        name: email
        description: This passengers email address
      - in: formData
        name: expediaEmailOptIn
        description: Whether to opt-in the users email to travel deals
      - in: formData
        name: firstName
        description: The first name of the traveler
      - in: formData
        name: gender
        description: TSA required field, MALE or FEMALE
      - in: formData
        name: knownTravelerNumber
        description: Passengers knownTravelerNumber(PreCheckNumber), a 9 digit number
      - in: formData
        name: lastName
        description: The last name of the traveler
      - in: formData
        name: middleName
        description: The middle name of the traveler
      - in: formData
        name: passengerCategory
        description: The passengers category
      - in: formData
        name: passportCountryCode
        description: Passport country, UPPERCASE three letter country code
      - in: formData
        name: password
        description: The password provided by the Expedia user
      - in: formData
        name: phone
        description: The phone number of the traveler
      - in: formData
        name: phoneCountryCode
        description: The country code of the phone number of the traveler
      - in: formData
        name: seatPreference
        description: Passengers seat preference
      - in: formData
        name: specialAssistanceOption
        description: Special assistance choice
      - in: formData
        name: title
        description: Title of passenger
      - in: formData
        name: TSARedressNumber
        description: Passengers TSA redress number, which is, in theory a 7 digit
          number
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Users