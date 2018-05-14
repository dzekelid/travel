---
swagger: "2.0"
info:
  title: AXA Assistance Requests to create a claim related to a travel accident.
  description: Requests to create a claim related to a travel accident.
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /insurance/vexp/travel_accident/claims:
    post:
      summary: Requests to create a claim related to a travel accident.
      description: Requests to create a claim related to a travel accident
      operationId: postInsuranceVexpTravel_accidentClaims
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - insurance
      - requestassistance
      - to
      - createclaim
      - related
      - totravel
      - accident.
definitions:
  version:
    properties:
      package:
        description: This is a default description.
        type: patch
      commit-sha:
        description: This is a default description.
        type: patch
  error:
    properties:
      status_code:
        description: This is a default description.
        type: patch
      error:
        description: This is a default description.
        type: patch
      error_description:
        description: This is a default description.
        type: patch
  country_light:
    properties:
      id:
        description: This is a default description.
        type: patch
      label:
        description: This is a default description.
        type: patch
  person:
    properties:
      title:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      birth_date:
        description: This is a default description.
        type: patch
      gender:
        description: This is a default description.
        type: patch
      nationalities:
        description: This is a default description.
        type: patch
  person_registration:
    properties:
      registration_type:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  address:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  phone:
    properties:
      phone_type:
        description: This is a default description.
        type: patch
      international_prefix:
        description: This is a default description.
        type: patch
      number:
        description: This is a default description.
        type: patch
  beneficiary:
    properties:
      person_registrations:
        description: This is a default description.
        type: patch
      phones:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  service:
    properties:
      service_id:
        description: This is a default description.
        type: patch
      operated_service:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      provider_assigned:
        description: This is a default description.
        type: patch
  case:
    properties:
      case_id:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      opened_at:
        description: This is a default description.
        type: patch
      updated_at:
        description: This is a default description.
        type: patch
      beneficiaries:
        description: This is a default description.
        type: patch
      services:
        description: This is a default description.
        type: patch
  world_health_organization_bulletins:
    properties:
      id:
        description: This is a default description.
        type: patch
      title:
        description: This is a default description.
        type: patch
      short_description:
        description: This is a default description.
        type: patch
      level:
        description: This is a default description.
        type: patch
      alert_date:
        description: This is a default description.
        type: patch
  axa_alerts:
    properties:
      id:
        description: This is a default description.
        type: patch
      title:
        description: This is a default description.
        type: patch
      short_description:
        description: This is a default description.
        type: patch
      level:
        description: This is a default description.
        type: patch
      end_date:
        description: This is a default description.
        type: patch
      content:
        description: This is a default description.
        type: patch
      alert_date:
        description: This is a default description.
        type: patch
  alerts:
    properties:
      world_health_organization_bulletins:
        description: This is a default description.
        type: patch
      axa_health_alerts:
        description: This is a default description.
        type: patch
      axa_security_alerts:
        description: This is a default description.
        type: patch
  passport_and_visa:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  airports:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  embassy:
    properties:
      label:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      type:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      website:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  national_embassies:
    properties:
      label:
        description: This is a default description.
        type: patch
      list:
        description: This is a default description.
        type: patch
  foreign_embassies:
    properties:
      label:
        description: This is a default description.
        type: patch
      list:
        description: This is a default description.
        type: patch
  holiday:
    properties:
      date:
        description: This is a default description.
        type: patch
      name:
        description: This is a default description.
        type: patch
  public_holidays:
    properties:
      label:
        description: This is a default description.
        type: patch
      list:
        description: This is a default description.
        type: patch
  daily_life:
    properties:
      label:
        description: This is a default description.
        type: patch
      office_hours:
        description: This is a default description.
        type: patch
      shopping_hours:
        description: This is a default description.
        type: patch
      banking_hours:
        description: This is a default description.
        type: patch
      post_office_hours:
        description: This is a default description.
        type: patch
      electricity:
        description: This is a default description.
        type: patch
      weights_measures:
        description: This is a default description.
        type: patch
      required_clothing:
        description: This is a default description.
        type: patch
      tipping_information:
        description: This is a default description.
        type: patch
  currency_converter:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  emergency_numbers:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
      ambulance:
        description: This is a default description.
        type: patch
      police:
        description: This is a default description.
        type: patch
      fire:
        description: This is a default description.
        type: patch
  country:
    properties:
      id:
        description: This is a default description.
        type: patch
      label:
        description: This is a default description.
        type: patch
  position:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 2:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  workshop:
    properties:
      id:
        description: This is a default description.
        type: patch
      name:
        description: This is a default description.
        type: patch
  distance:
    properties:
      value:
        description: This is a default description.
        type: patch
      unit:
        description: This is a default description.
        type: patch
      is_as_crow_flies:
        description: This is a default description.
        type: patch
  workshopResponse:
    properties: []
  availability:
    properties:
      from:
        description: This is a default description.
        type: patch
      to:
        description: This is a default description.
        type: patch
  rate:
    properties:
      rating:
        description: This is a default description.
        type: patch
      comments:
        description: This is a default description.
        type: patch
  location:
    properties:
      latitude:
        description: This is a default description.
        type: patch
      longitude:
        description: This is a default description.
        type: patch
  roadside_provider:
    properties:
      provider_id:
        description: This is a default description.
        type: patch
      name:
        description: This is a default description.
        type: patch
  provider_kind:
    properties:
      id:
        description: This is a default description.
        type: patch
      label:
        description: This is a default description.
        type: patch
  Model 4:
    properties:
      lat:
        description: This is a default description.
        type: patch
      lng:
        description: This is a default description.
        type: patch
      distance_in_meters:
        description: This is a default description.
        type: patch
  Model 5:
    properties:
      city:
        description: This is a default description.
        type: patch
      zipcode:
        description: This is a default description.
        type: patch
      area:
        description: This is a default description.
        type: patch
      country_id:
        description: This is a default description.
        type: patch
      street:
        description: This is a default description.
        type: patch
  provider:
    properties:
      id:
        description: This is a default description.
        type: patch
      name:
        description: This is a default description.
        type: patch
      kind:
        description: This is a default description.
        type: patch
      speciality:
        description: This is a default description.
        type: patch
      international_phone_number:
        description: This is a default description.
        type: patch
      website:
        description: This is a default description.
        type: patch
      phone_admission:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
      international_fax_number:
        description: This is a default description.
        type: patch
      AXA_preferred:
        description: This is a default description.
        type: patch
  provider_speciality:
    properties:
      id:
        description: This is a default description.
        type: patch
      label:
        description: This is a default description.
        type: patch
  appointment_period:
    properties:
      from:
        description: This is a default description.
        type: patch
      to:
        description: This is a default description.
        type: patch
  effective_period:
    properties:
      from:
        description: This is a default description.
        type: patch
      to:
        description: This is a default description.
        type: patch
  Model 6:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  prescription:
    properties:
      prescription_id:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      valid_until:
        description: This is a default description.
        type: patch
      recipient_type:
        description: This is a default description.
        type: patch
  medical_consultation:
    properties:
      consultation_id:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      phones:
        description: This is a default description.
        type: patch
      reason:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
      customer_journey_step:
        description: This is a default description.
        type: patch
      is_the_requester_the_patient:
        description: This is a default description.
        type: patch
      prescriptions:
        description: This is a default description.
        type: patch
  risk:
    properties:
      risk:
        description: This is a default description.
        type: patch
      rating:
        description: This is a default description.
        type: patch
  risks_ratings:
    properties:
      label:
        description: This is a default description.
        type: patch
      list:
        description: This is a default description.
        type: patch
  general_info:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  security_cards:
    properties: []
  vaccinations:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  health_risks:
    properties:
      label:
        description: This is a default description.
        type: patch
      bird:
        description: This is a default description.
        type: patch
      traveler:
        description: This is a default description.
        type: patch
      malaria:
        description: This is a default description.
        type: patch
      special:
        description: This is a default description.
        type: patch
      food:
        description: This is a default description.
        type: patch
      common:
        description: This is a default description.
        type: patch
  first_aid_kit:
    properties:
      label:
        description: This is a default description.
        type: patch
      desc:
        description: This is a default description.
        type: patch
  health_cards:
    properties: []
  alertsByCountry:
    properties:
      axa_health_alerts:
        description: This is a default description.
        type: patch
      axa_security_alerts:
        description: This is a default description.
        type: patch
  vehicle:
    properties:
      vin_number:
        description: This is a default description.
        type: patch
      registration_number:
        description: This is a default description.
        type: patch
      brand:
        description: This is a default description.
        type: patch
      model:
        description: This is a default description.
        type: patch
  Model 9:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 10:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 11:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  technician:
    properties:
      truck_registration_number:
        description: This is a default description.
        type: patch
  assignment_response:
    properties:
      assignment_id:
        description: This is a default description.
        type: patch
      provider_id:
        description: This is a default description.
        type: patch
      customer_id:
        description: This is a default description.
        type: patch
      quote_id:
        description: This is a default description.
        type: patch
      service:
        description: This is a default description.
        type: patch
      place_type:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      to_schedule_on:
        description: This is a default description.
        type: patch
      expected_on:
        description: This is a default description.
        type: patch
  Model 12:
    properties:
      title:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      birth_date:
        description: This is a default description.
        type: patch
      gender:
        description: This is a default description.
        type: patch
      nationalities:
        description: This is a default description.
        type: patch
  contract_holder:
    properties:
      customer_id:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  product_criteria:
    properties:
      bank_identification_number:
        description: This is a default description.
        type: patch
  extended_warranty_information:
    properties:
      original_period:
        description: This is a default description.
        type: patch
  appliance_certificate:
    properties:
      beneficiaries:
        description: This is a default description.
        type: patch
      certificate_id:
        description: This is a default description.
        type: patch
      certificate_type_name:
        description: This is a default description.
        type: patch
      created_at:
        description: This is a default description.
        type: patch
  car_rental_information:
    properties:
      from:
        description: This is a default description.
        type: patch
      to:
        description: This is a default description.
        type: patch
      country_origin:
        description: This is a default description.
        type: patch
      city_origin:
        description: This is a default description.
        type: patch
      country_destination:
        description: This is a default description.
        type: patch
      city_destination:
        description: This is a default description.
        type: patch
      is_international_trip:
        description: This is a default description.
        type: patch
      rental_company:
        description: This is a default description.
        type: patch
      reservation_number:
        description: This is a default description.
        type: patch
      vehicle_type:
        description: This is a default description.
        type: patch
  car_rental_certificate:
    properties:
      beneficiaries:
        description: This is a default description.
        type: patch
      certificate_id:
        description: This is a default description.
        type: patch
      certificate_type_name:
        description: This is a default description.
        type: patch
      created_at:
        description: This is a default description.
        type: patch
  Model 14:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  Model 15:
    properties:
      international_prefix:
        description: This is a default description.
        type: patch
      number:
        description: This is a default description.
        type: patch
  fax:
    properties:
      international_prefix:
        description: This is a default description.
        type: patch
      number:
        description: This is a default description.
        type: patch
  selected_recipient:
    properties:
      name:
        description: This is a default description.
        type: patch
      comments:
        description: This is a default description.
        type: patch
      reference:
        description: This is a default description.
        type: patch
  attachment:
    properties:
      content_type:
        description: This is a default description.
        type: patch
      is_original:
        description: This is a default description.
        type: patch
      content_url:
        description: This is a default description.
        type: patch
  prescription_response:
    properties:
      medical_consultation_id:
        description: This is a default description.
        type: patch
      prescription_id:
        description: This is a default description.
        type: patch
      status:
        description: This is a default description.
        type: patch
      valid_until:
        description: This is a default description.
        type: patch
      recipient_type:
        description: This is a default description.
        type: patch
  Channel Response:
    properties:
      value:
        description: This is a default description.
        type: patch
  Model 16:
    properties:
      confirmation_id:
        description: This is a default description.
        type: patch
  policy_holder:
    properties:
      policy_holder_id:
        description: This is a default description.
        type: patch
      reference:
        description: This is a default description.
        type: patch
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
  Model 17:
    properties:
      policy_holder_id:
        description: This is a default description.
        type: patch
      reference:
        description: This is a default description.
        type: patch
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
  Model 19:
    properties:
      policy_holder_id:
        description: This is a default description.
        type: patch
      reference:
        description: This is a default description.
        type: patch
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
  medical_consultation_creation:
    properties:
      phones:
        description: This is a default description.
        type: patch
      reason:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
      customer_journey_step:
        description: This is a default description.
        type: patch
      is_the_requester_the_patient:
        description: This is a default description.
        type: patch
  medical_consultation_response:
    properties:
      consultation_id:
        description: This is a default description.
        type: patch
  Model 21:
    properties:
      customer_id:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  Model 22:
    properties:
      phone_type:
        description: This is a default description.
        type: patch
      international_prefix:
        description: This is a default description.
        type: patch
      number:
        description: This is a default description.
        type: patch
  Model 23:
    properties:
      consent_type:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  to_be_reviewed_information:
    properties:
      account_billing_street:
        description: This is a default description.
        type: patch
      account_billing_city:
        description: This is a default description.
        type: patch
      visa_exp_city:
        description: This is a default description.
        type: patch
      claim_phone:
        description: This is a default description.
        type: patch
      claim_fax:
        description: This is a default description.
        type: patch
      claim_person_other_phone:
        description: This is a default description.
        type: patch
      bin_bin_issuername:
        description: This is a default description.
        type: patch
      claim_bin_4LastDigits:
        description: This is a default description.
        type: patch
      bin_number:
        description: This is a default description.
        type: patch
  Model 24:
    properties:
      wire_code_type:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  Model 25:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  Model 26:
    properties:
      registration_type:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  holder:
    properties:
      name:
        description: This is a default description.
        type: patch
      registrations:
        description: This is a default description.
        type: patch
  bank:
    properties:
      name:
        description: This is a default description.
        type: patch
      bank_code:
        description: This is a default description.
        type: patch
      branch_code:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
  beneficiary_account:
    properties:
      bank_account_number:
        description: This is a default description.
        type: patch
      wire_codes:
        description: This is a default description.
        type: patch
      is_current_account:
        description: This is a default description.
        type: patch
  intermediary_account:
    properties:
      bank_account_number:
        description: This is a default description.
        type: patch
      wire_codes:
        description: This is a default description.
        type: patch
      is_current_account:
        description: This is a default description.
        type: patch
  Model 27:
    properties:
      information_type:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  reimbursement_information:
    properties:
      additional_information:
        description: This is a default description.
        type: patch
  general_information:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
      claim_phones:
        description: This is a default description.
        type: patch
      consents:
        description: This is a default description.
        type: patch
  appliance_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_that_applies:
        description: This is a default description.
        type: patch
      Please_indicate_the_amount:
        description: This is a default description.
        type: patch
      Have_you_made_any_previous_claim:
        description: This is a default description.
        type: patch
      On_what_date:
        description: This is a default description.
        type: patch
      Was_the_purchased_item_charged_in_full:
        description: This is a default description.
        type: patch
  create_claim_request:
    properties: []
  create_claim_response:
    properties:
      claim_id:
        description: This is a default description.
        type: patch
  Model 28:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
      claim_phones:
        description: This is a default description.
        type: patch
      consents:
        description: This is a default description.
        type: patch
  car_rental_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Driver_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Start_rental_date:
        description: This is a default description.
        type: patch
      End_rental_date:
        description: This is a default description.
        type: patch
      Incident_date:
        description: This is a default description.
        type: patch
      Time_of_the_accident:
        description: This is a default description.
        type: patch
  Model 29:
    properties: []
  Model 30:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
      claim_phones:
        description: This is a default description.
        type: patch
      consents:
        description: This is a default description.
        type: patch
  corporate_liability_claim_information:
    properties:
      BINNumber:
        description: This is a default description.
        type: patch
      Issuer_Name_Issuer_Information:
        description: This is a default description.
        type: patch
      Street_Address_Issuer_Information:
        description: This is a default description.
        type: patch
      City_Issuer_Information:
        description: This is a default description.
        type: patch
      Country_Issuer_Information:
        description: This is a default description.
        type: patch
      Postal_Code_Issuer_Information:
        description: This is a default description.
        type: patch
      Contact_person_Issuer_Information:
        description: This is a default description.
        type: patch
      Total_Number_of_Valid_Company_Accounts_I:
        description: This is a default description.
        type: patch
      Cardholder_s_Credit_Limit_Issuer_Informa:
        description: This is a default description.
        type: patch
      CurrencyIsoCode:
        description: This is a default description.
        type: patch
  Model 31:
    properties: []
  Model 32:
    properties:
      Date_of_purchase_of_items:
        description: This is a default description.
        type: patch
      Description_of_claimed_cost:
        description: This is a default description.
        type: patch
      Amount_Claimed:
        description: This is a default description.
        type: patch
      Form_of_Payment:
        description: This is a default description.
        type: patch
  delayed_luggage_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Was_the_full_trip_charged_to_your_Visa:
        description: This is a default description.
        type: patch
      From_Planned_day_of_trip:
        description: This is a default description.
        type: patch
      To_Planned_day_of_trip:
        description: This is a default description.
        type: patch
      Day_Arrival_From:
        description: This is a default description.
        type: patch
      Time_Arrival:
        description: This is a default description.
        type: patch
  Model 33:
    properties: []
  Model 34:
    properties:
      Description_of_claimed_costs:
        description: This is a default description.
        type: patch
      Amount_Claimed:
        description: This is a default description.
        type: patch
  delayed_trip_claim_information:
    properties:
      Name_of_requestor:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_covering:
        description: This is a default description.
        type: patch
      Reimbursed_for_any_portion_of_the_cause:
        description: This is a default description.
        type: patch
      Amount_Reimbursed:
        description: This is a default description.
        type: patch
      Total_amount_claimed:
        description: This is a default description.
        type: patch
      Start_trip_date:
        description: This is a default description.
        type: patch
  Model 35:
    properties: []
  Model 36:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
      claim_phones:
        description: This is a default description.
        type: patch
      consents:
        description: This is a default description.
        type: patch
  Model 37:
    properties:
      Description_of_items:
        description: This is a default description.
        type: patch
      Name_of_owner:
        description: This is a default description.
        type: patch
      Place_of_purchase_of_items:
        description: This is a default description.
        type: patch
      Date_of_purchase_of_items:
        description: This is a default description.
        type: patch
      Aproximate_value_of_items:
        description: This is a default description.
        type: patch
  lost_baggage_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_loss:
        description: This is a default description.
        type: patch
      Have_you_submitted_a_formal_complaint:
        description: This is a default description.
        type: patch
      Please_explain_why:
        description: This is a default description.
        type: patch
      Start_trip_date:
        description: This is a default description.
        type: patch
      End_trip_date:
        description: This is a default description.
        type: patch
  Model 38:
    properties: []
  Model 39:
    properties:
      Date_of_purchase_of_items:
        description: This is a default description.
        type: patch
      Description_of_claimed_cost:
        description: This is a default description.
        type: patch
      Amount_Claimed:
        description: This is a default description.
        type: patch
      Form_of_Payment:
        description: This is a default description.
        type: patch
  missed_flight_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_covering:
        description: This is a default description.
        type: patch
      Amount_paid_by_other_insurance:
        description: This is a default description.
        type: patch
      Airline_offer_any_compensation:
        description: This is a default description.
        type: patch
      Form_of_payment:
        description: This is a default description.
        type: patch
      Start_trip_date:
        description: This is a default description.
        type: patch
  Model 41:
    properties: []
  Model 42:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
      claim_phones:
        description: This is a default description.
        type: patch
      consents:
        description: This is a default description.
        type: patch
  price_protection_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_that_applies:
        description: This is a default description.
        type: patch
      Please_indicate_the_amount:
        description: This is a default description.
        type: patch
      Have_you_made_any_previous_claim:
        description: This is a default description.
        type: patch
      On_what_date:
        description: This is a default description.
        type: patch
      Was_the_purchased_item_charged_in_full:
        description: This is a default description.
        type: patch
  Model 43:
    properties: []
  Select_Assault_Option_EqualsTo_0:
    properties:
      BINNumber:
        description: This is a default description.
        type: patch
      Select_Assault_Option:
        description: This is a default description.
        type: patch
      Description_of_Incident:
        description: This is a default description.
        type: patch
      Incident_date:
        description: This is a default description.
        type: patch
      Time_when_did_the_accident_occur:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Country_Place_if_accident:
        description: This is a default description.
        type: patch
      City_where_did_the_accident_occur:
        description: This is a default description.
        type: patch
      Street_where_did_the_accident_occur:
        description: This is a default description.
        type: patch
      Withdrawn_Amount:
        description: This is a default description.
        type: patch
  stolen_cash_claim_information:
    properties: []
  Model 44:
    properties: []
  Model 45:
    properties:
      name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
  Model 46:
    properties:
      name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
  Accidental_dismemberment:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Type_and_number_of_official:
        description: This is a default description.
        type: patch
      Relationship_of_the_deceased_with_the:
        description: This is a default description.
        type: patch
      Other_Relationship_of_the_deceased:
        description: This is a default description.
        type: patch
      Address_Travel_Accident_Insurance:
        description: This is a default description.
        type: patch
      City:
        description: This is a default description.
        type: patch
      State:
        description: This is a default description.
        type: patch
      Home_Travael_Accident_Insurance:
        description: This is a default description.
        type: patch
      Office_Travel_Accident_Insurance:
        description: This is a default description.
        type: patch
      Other_Travel_Accident_Insurance:
        description: This is a default description.
        type: patch
  travel_accident_claim_information:
    properties:
      Select_the_reason_of_accident:
        description: This is a default description.
        type: patch
  Model 47:
    properties: []
  trip_claim_information:
    properties:
      Select_the_reason_of_accident:
        description: This is a default description.
        type: patch
  Model 48:
    properties: []
  Model 49:
    properties:
      Description_of_items_claimed:
        description: This is a default description.
        type: patch
      Expenses_incurred:
        description: This is a default description.
        type: patch
      Amount_reimbursed_by_other_companies:
        description: This is a default description.
        type: patch
      Amount_Claimed:
        description: This is a default description.
        type: patch
  trip_cancellation_claim_information:
    properties:
      Claimant_name:
        description: This is a default description.
        type: patch
      Relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Other_relationship_to_cardholder:
        description: This is a default description.
        type: patch
      Sex:
        description: This is a default description.
        type: patch
      Date_of_Birth:
        description: This is a default description.
        type: patch
      Do_you_have_other_insurance_covering:
        description: This is a default description.
        type: patch
      Reimbursed_for_any_portion_of_the_cause:
        description: This is a default description.
        type: patch
      From_Planned_day_of_trip:
        description: This is a default description.
        type: patch
      To_Planned_day_of_trip:
        description: This is a default description.
        type: patch
      Date_of_interruption_cancellation:
        description: This is a default description.
        type: patch
  Model 51:
    properties: []
  assignment_creation_resquest:
    properties:
      provider_id:
        description: This is a default description.
        type: patch
      customer_id:
        description: This is a default description.
        type: patch
      quote_id:
        description: This is a default description.
        type: patch
      service:
        description: This is a default description.
        type: patch
      place_type:
        description: This is a default description.
        type: patch
      to_schedule_on:
        description: This is a default description.
        type: patch
  forgot_password_request:
    properties:
      username:
        description: This is a default description.
        type: patch
      confirmation_language:
        description: This is a default description.
        type: patch
      confirmation_template:
        description: This is a default description.
        type: patch
      channel_type:
        description: This is a default description.
        type: patch
  user_request:
    properties:
      invitation_code:
        description: This is a default description.
        type: patch
      username:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      password:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
      confirmation_language:
        description: This is a default description.
        type: patch
      confirmation_template:
        description: This is a default description.
        type: patch
  user_response:
    properties:
      id:
        description: This is a default description.
        type: patch
      username:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
      confirmation_id:
        description: This is a default description.
        type: patch
  create_electric_declaration_request:
    properties:
      subscription_id:
        description: This is a default description.
        type: patch
      event_date:
        description: This is a default description.
        type: patch
  create_electric_declaration_response:
    properties:
      declaration_id:
        description: This is a default description.
        type: patch
  create_gas_response:
    properties:
      declaration_id:
        description: This is a default description.
        type: patch
  amount:
    properties:
      value:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
  Model 52:
    properties:
      appliance_description:
        description: This is a default description.
        type: patch
      brand:
        description: This is a default description.
        type: patch
      model:
        description: This is a default description.
        type: patch
      purchase_date:
        description: This is a default description.
        type: patch
  create_certificate:
    properties:
      beneficiaries:
        description: This is a default description.
        type: patch
  create_certificate_response:
    properties:
      certificate_id:
        description: This is a default description.
        type: patch
  Model 53:
    properties:
      beneficiaries:
        description: This is a default description.
        type: patch
  travel_information:
    properties:
      from:
        description: This is a default description.
        type: patch
      to:
        description: This is a default description.
        type: patch
      is_one_way_travel:
        description: This is a default description.
        type: patch
      country_origin:
        description: This is a default description.
        type: patch
      city_origin:
        description: This is a default description.
        type: patch
      country_destination:
        description: This is a default description.
        type: patch
      city_destination:
        description: This is a default description.
        type: patch
      is_international_trip:
        description: This is a default description.
        type: patch
  Model 54:
    properties:
      beneficiaries:
        description: This is a default description.
        type: patch
  context:
    properties:
      country:
        description: This is a default description.
        type: patch
      language:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
  additional_data:
    properties:
      name:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  Model 56:
    properties:
      title:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      birth_date:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      zip_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
      phone:
        description: This is a default description.
        type: patch
  Model 58:
    properties:
      title:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      birth_date:
        description: This is a default description.
        type: patch
      additional_data:
        description: This is a default description.
        type: patch
  travel_date:
    properties:
      from:
        description: This is a default description.
        type: patch
      duration:
        description: This is a default description.
        type: patch
  trip:
    properties:
      origin:
        description: This is a default description.
        type: patch
      destination:
        description: This is a default description.
        type: patch
      cost:
        description: This is a default description.
        type: patch
  travelers:
    properties:
      adults:
        description: This is a default description.
        type: patch
      children:
        description: This is a default description.
        type: patch
      infants:
        description: This is a default description.
        type: patch
      seniors:
        description: This is a default description.
        type: patch
      oldest_traveler_age:
        description: This is a default description.
        type: patch
  Model 60:
    properties: []
  loyalty:
    properties:
      program:
        description: This is a default description.
        type: patch
      level:
        description: This is a default description.
        type: patch
  optional_travel_information:
    properties:
      includes_a_stop_over:
        description: This is a default description.
        type: patch
      is_fare_flexible:
        description: This is a default description.
        type: patch
      category:
        description: This is a default description.
        type: patch
      number_of_checked_in_luggage:
        description: This is a default description.
        type: patch
      product_customization:
        description: This is a default description.
        type: patch
  policy_undefined_criteria:
    properties:
      name:
        description: This is a default description.
        type: patch
      value:
        description: This is a default description.
        type: patch
  policy_subscription:
    properties:
      partner_key:
        description: This is a default description.
        type: patch
      product_code:
        description: This is a default description.
        type: patch
      product_price:
        description: This is a default description.
        type: patch
      beneficiaries:
        description: This is a default description.
        type: patch
      payment_method_id:
        description: This is a default description.
        type: patch
      undefined_criteria:
        description: This is a default description.
        type: patch
  policy_subscription_response:
    properties:
      policy_number:
        description: This is a default description.
        type: patch
  quote_context:
    properties:
      country:
        description: This is a default description.
        type: patch
      language:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
  quote_travel_date:
    properties:
      from:
        description: This is a default description.
        type: patch
      duration:
        description: This is a default description.
        type: patch
  quote_trip:
    properties:
      origin:
        description: This is a default description.
        type: patch
      destination:
        description: This is a default description.
        type: patch
      cost:
        description: This is a default description.
        type: patch
  quote_travelers:
    properties:
      adults:
        description: This is a default description.
        type: patch
      children:
        description: This is a default description.
        type: patch
      infants:
        description: This is a default description.
        type: patch
      seniors:
        description: This is a default description.
        type: patch
      oldest_traveler_age:
        description: This is a default description.
        type: patch
  quoting_criteria:
    properties: []
  quote_loyalty:
    properties:
      program:
        description: This is a default description.
        type: patch
      level:
        description: This is a default description.
        type: patch
  quote_customization_criteria:
    properties:
      includes_a_stop_over:
        description: This is a default description.
        type: patch
      is_fare_flexible:
        description: This is a default description.
        type: patch
      category:
        description: This is a default description.
        type: patch
      number_of_checked_in_luggage:
        description: This is a default description.
        type: patch
      product_customization:
        description: This is a default description.
        type: patch
  quote_request:
    properties:
      partner_key:
        description: This is a default description.
        type: patch
      undefined_criteria:
        description: This is a default description.
        type: patch
  Model 61:
    properties:
      country:
        description: This is a default description.
        type: patch
      language:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
  price:
    properties:
      total_price_with_taxes:
        description: This is a default description.
        type: patch
      total_taxes:
        description: This is a default description.
        type: patch
  guarantee:
    properties:
      code:
        description: This is a default description.
        type: patch
      label:
        description: This is a default description.
        type: patch
      included:
        description: This is a default description.
        type: patch
      limit:
        description: This is a default description.
        type: patch
  coverage:
    properties:
      summary:
        description: This is a default description.
        type: patch
      link:
        description: This is a default description.
        type: patch
      guarantees:
        description: This is a default description.
        type: patch
  product:
    properties:
      code:
        description: This is a default description.
        type: patch
      name:
        description: This is a default description.
        type: patch
      description:
        description: This is a default description.
        type: patch
      order:
        description: This is a default description.
        type: patch
      terms_and_conditions:
        description: This is a default description.
        type: patch
      coverages:
        description: This is a default description.
        type: patch
  quote_response:
    properties:
      quote_id:
        description: This is a default description.
        type: patch
      products:
        description: This is a default description.
        type: patch
  rate_medical_consultation_request:
    properties:
      rating:
        description: This is a default description.
        type: patch
      comments:
        description: This is a default description.
        type: patch
  medical_consultation_cancellation:
    properties:
      cancelation_reason:
        description: This is a default description.
        type: patch
  Model 62:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 63:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 64:
    properties:
      brand:
        description: This is a default description.
        type: patch
      model:
        description: This is a default description.
        type: patch
  Model 65:
    properties:
      service:
        description: This is a default description.
        type: patch
      place_type:
        description: This is a default description.
        type: patch
      to_schedule_on:
        description: This is a default description.
        type: patch
  Model 66:
    properties:
      provider_id:
        description: This is a default description.
        type: patch
      url:
        description: This is a default description.
        type: patch
  Model 67:
    properties:
      longitude:
        description: This is a default description.
        type: patch
      latitude:
        description: This is a default description.
        type: patch
  Model 68:
    properties:
      value:
        description: This is a default description.
        type: patch
      unit:
        description: This is a default description.
        type: patch
      is_as_crow_flies:
        description: This is a default description.
        type: patch
  Model 69:
    properties:
      value:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
  quote:
    properties:
      quote_id:
        description: This is a default description.
        type: patch
  forgot_password_confirmation_request:
    properties:
      username:
        description: This is a default description.
        type: patch
      confirmation_token:
        description: This is a default description.
        type: patch
      password:
        description: This is a default description.
        type: patch
  user_confirmation_request:
    properties:
      confirmation_id:
        description: This is a default description.
        type: patch
      confirmation_token:
        description: This is a default description.
        type: patch
      otp:
        description: This is a default description.
        type: patch
  send_otp_request:
    properties:
      confirmation_id:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
  change_password_request:
    properties:
      new_password:
        description: This is a default description.
        type: patch
      old_password:
        description: This is a default description.
        type: patch
  Model 70:
    properties:
      rating:
        description: This is a default description.
        type: patch
      comments:
        description: This is a default description.
        type: patch
  assignment_rate_request:
    properties: []
  assignment_confirm_request:
    properties:
      payment_transaction_id:
        description: This is a default description.
        type: patch
  assignment_cancel_request:
    properties:
      reason:
        description: This is a default description.
        type: patch
  Model 71:
    properties:
      value:
        description: This is a default description.
        type: patch
      currency:
        description: This is a default description.
        type: patch
  assignment_cancel_response:
    properties:
      message:
        description: This is a default description.
        type: patch
  user_confirmation_resend_request:
    properties:
      invitation_code:
        description: This is a default description.
        type: patch
      username:
        description: This is a default description.
        type: patch
      confirmation_language:
        description: This is a default description.
        type: patch
      confirmation_template:
        description: This is a default description.
        type: patch
  Channel Confirmation Response:
    properties:
      confirmation_id:
        description: This is a default description.
        type: patch
      confirmation_token:
        description: This is a default description.
        type: patch
  confirm_electric_declaration_request:
    properties:
      confirmation_date:
        description: This is a default description.
        type: patch
  contact_request:
    properties:
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      mobile_phone_number:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  contact_response:
    properties:
      contact_id:
        description: This is a default description.
        type: patch
  close_electric_declaration_request:
    properties:
      closure_date:
        description: This is a default description.
        type: patch
      reason_description:
        description: This is a default description.
        type: patch
  Model 72:
    properties:
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      mobile_phone_number:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  close_glaziery_request:
    properties:
      closure_date:
        description: This is a default description.
        type: patch
      reason_description:
        description: This is a default description.
        type: patch
  cancel_policy:
    properties:
      cancellation_date:
        description: This is a default description.
        type: patch
      reason_description:
        description: This is a default description.
        type: patch
  Model 73:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  Model 74:
    properties:
      name:
        description: This is a default description.
        type: patch
      comments:
        description: This is a default description.
        type: patch
      reference:
        description: This is a default description.
        type: patch
  send_prescription_request:
    properties: []
  Model 75:
    properties:
      street_address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      locality:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      subdivision:
        description: This is a default description.
        type: patch
      state:
        description: This is a default description.
        type: patch
  medical_consultation_update:
    properties:
      phones:
        description: This is a default description.
        type: patch
      reason:
        description: This is a default description.
        type: patch
      channel:
        description: This is a default description.
        type: patch
      customer_journey_step:
        description: This is a default description.
        type: patch
      is_the_requester_the_patient:
        description: This is a default description.
        type: patch
  update_identity_request:
    properties:
      username:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
  detail_electric_declaration_request:
    properties:
      is_total_breakdown:
        description: This is a default description.
        type: patch
      is_breaker_on:
        description: This is a default description.
        type: patch
      is_ground_fault_circuit_interrupter:
        description: This is a default description.
        type: patch
      is_untimely_breakdown:
        description: This is a default description.
        type: patch
      is_fix_hour_disjunction:
        description: This is a default description.
        type: patch
      is_disjunction_randomly:
        description: This is a default description.
        type: patch
      is_various_breakdown:
        description: This is a default description.
        type: patch
      is_day_night_contactor:
        description: This is a default description.
        type: patch
      is_day_night_contactor_activated:
        description: This is a default description.
        type: patch
      is_electric_water_heater:
        description: This is a default description.
        type: patch
  detail_gas_request:
    properties:
      is_gas_leakage:
        description: This is a default description.
        type: patch
      is_supplier_alerted:
        description: This is a default description.
        type: patch
      is_leakage_on_gas_distribution:
        description: This is a default description.
        type: patch
      suggested_decision:
        description: This is a default description.
        type: patch
      additional_information:
        description: This is a default description.
        type: patch
  detail_glaziery_request:
    properties:
      is_glaziery_damage:
        description: This is a default description.
        type: patch
      is_forced_vandalism:
        description: This is a default description.
        type: patch
      is_covered_address:
        description: This is a default description.
        type: patch
      suggested_decision:
        description: This is a default description.
        type: patch
      additional_information:
        description: This is a default description.
        type: patch
  detail_home_appliance_request:
    properties:
      is_washer_dryer_breakdown:
        description: This is a default description.
        type: patch
      is_under_manufacturer_warranty:
        description: This is a default description.
        type: patch
      is_mechanical_breakdown:
        description: This is a default description.
        type: patch
      is_inside_housing_coverage:
        description: This is a default description.
        type: patch
      is_invoice_available:
        description: This is a default description.
        type: patch
      is_baking_trail_breakdown:
        description: This is a default description.
        type: patch
      is_hifi_video_breakdown:
        description: This is a default description.
        type: patch
      is_fridge_freezer_breakdown:
        description: This is a default description.
        type: patch
      suggested_decision:
        description: This is a default description.
        type: patch
      additional_information:
        description: This is a default description.
        type: patch
  detail_locksmithing_request:
    properties:
      is_stolen_key:
        description: This is a default description.
        type: patch
      is_lost_key:
        description: This is a default description.
        type: patch
      is_locksmithing_damage:
        description: This is a default description.
        type: patch
      is_forced_vandalism:
        description: This is a default description.
        type: patch
      is_covered_address:
        description: This is a default description.
        type: patch
      suggested_decision:
        description: This is a default description.
        type: patch
      additional_information:
        description: This is a default description.
        type: patch
  detail_water_request:
    properties:
      is_inside_housing_leakage:
        description: This is a default description.
        type: patch
      is_valve_flush_boiler_water_heater_softener:
        description: This is a default description.
        type: patch
      is_after_water_meter:
        description: This is a default description.
        type: patch
      is_leakage_visible:
        description: This is a default description.
        type: patch
      is_inside_waterlogging:
        description: This is a default description.
        type: patch
      is_inside_waterlogging_caused_by_rainwater:
        description: This is a default description.
        type: patch
      is_outside_waterlogging:
        description: This is a default description.
        type: patch
      is_outside_waterlogging_caused_by_rainwater:
        description: This is a default description.
        type: patch
      is_cap_inside_housing:
        description: This is a default description.
        type: patch
      is_skeptic_tank_grease_trap_drained:
        description: This is a default description.
        type: patch
  update_prescription_request:
    properties: []
  policy_holder_update:
    properties:
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      mobile_phone_number:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  Model 76:
    properties:
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      mobile_phone_number:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
  Model 77:
    properties:
      title:
        description: This is a default description.
        type: patch
      last_name:
        description: This is a default description.
        type: patch
      first_name:
        description: This is a default description.
        type: patch
      address:
        description: This is a default description.
        type: patch
      postal_code:
        description: This is a default description.
        type: patch
      city:
        description: This is a default description.
        type: patch
      country:
        description: This is a default description.
        type: patch
      phone_number:
        description: This is a default description.
        type: patch
      mobile_phone_number:
        description: This is a default description.
        type: patch
      email:
        description: This is a default description.
        type: patch
x-collection-name: AXA Assistance
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