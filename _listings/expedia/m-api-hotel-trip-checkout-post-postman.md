{
  "info": {
    "name": "Expedia Checkout",
    "_postman_id": "6986c576-e9c7-46f0-81e4-a6eb3df83764",
    "description": "Mobile API Hotels Checkout",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "81eaf142-0fb9-452e-a213-fe9d14c8382f",
          "name": "hotels-checkout",
          "request": {
            "url": "http://apim.expedia.com/x/m/api/hotel/trip/checkout",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "bedTypeId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Parameter that indicates the selected bed Type"
                },
                {
                  "key": "checkInDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "Check in date in ISO format (yyyy-MM-dd)"
                },
                {
                  "key": "checkOutDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "Check out date in ISO format (yyyy-MM-DD)"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": "The city of the traveler's billing address"
                },
                {
                  "key": "country",
                  "value": "{}",
                  "disabled": false,
                  "description": "The 3 letter country code of the traveler's billing address"
                },
                {
                  "key": "creditCardNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "The credit card number used for this booking, if checking out with a new card"
                },
                {
                  "key": "cvv",
                  "value": "{}",
                  "disabled": false,
                  "description": "The CVV of the traveler's credit card used for this booking"
                },
                {
                  "key": "doIThinkImSignedIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "As a client I am checking-out with the assumption that I am signed in"
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "This passenger's email address"
                },
                {
                  "key": "expectedCardFee",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expected credit card fee, as returned by the createTrip call in the validFormsOfPayment object for whatever credit card the user is paying with"
                },
                {
                  "key": "expectedCardFeeCurrencyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Three letter 4217 ISO currency code of the expected total price"
                },
                {
                  "key": "expectedFareCurrencyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Three letter 4217 ISO currency code of the expected credit card fee"
                },
                {
                  "key": "expectedTotalFare",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expected total price of the trip, matching exactly whatever the user last saw"
                },
                {
                  "key": "expediaEmailOptIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to opt-in the user's email to travel deals"
                },
                {
                  "key": "expirationDateMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expiration date month of the credit card used for this booking"
                },
                {
                  "key": "expirationDateYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "The 4 digit expiration date year of the credit card used for this booking"
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The first name of the traveler"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The last name of the traveler"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The middle name of the traveler"
                },
                {
                  "key": "nameOnCard",
                  "value": "{}",
                  "disabled": false,
                  "description": "The card holder's name"
                },
                {
                  "key": "omniturePartnerId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Omniture partner identification string"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "The password provided by the expedia user"
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "The phone number of the traveler"
                },
                {
                  "key": "phoneCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The country code of the phone number of the traveler"
                },
                {
                  "key": "postalCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The postal code of the traveler's billing address"
                },
                {
                  "key": "prettyPrint",
                  "value": "{}",
                  "disabled": false,
                  "description": "If true, return JSON with tabs, spaces and newlines to be human readable"
                },
                {
                  "key": "rooms",
                  "value": "{}",
                  "disabled": false,
                  "description": "A list of room preferences to be applied to the rooms being booked"
                },
                {
                  "key": "rooms[0].accessibilityOptionIds",
                  "value": "{}",
                  "disabled": false,
                  "description": "A Comma Separated Value of accessibility option Ids"
                },
                {
                  "key": "rooms[0].specialRequests",
                  "value": "{}",
                  "disabled": false,
                  "description": "A text field for special requests"
                },
                {
                  "key": "sendEmailConfirmation",
                  "value": "{}",
                  "disabled": false,
                  "description": "Used to check if confirmation email needs to be sent or not"
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": "The state (or province) of the traveler's billing address"
                },
                {
                  "key": "storeCreditCardInUserProfile",
                  "value": "{}",
                  "disabled": false,
                  "description": "Indicates whether to save the credit card information as a stored credit card in the user profile"
                },
                {
                  "key": "storedCreditCardId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The GUID for the stored credit card information to be used for payment"
                },
                {
                  "key": "streetAddress",
                  "value": "{}",
                  "disabled": false,
                  "description": "The street part of the credit card owner's billing address"
                },
                {
                  "key": "streetAddress2",
                  "value": "{}",
                  "disabled": false,
                  "description": "Apartment or suite number of the traveler's billing address"
                },
                {
                  "key": "suppressFinalBooking",
                  "value": "{}",
                  "disabled": false,
                  "description": "If true, do not actually charge for and book the trip, stop after creating the itinerary"
                },
                {
                  "key": "tealeafTransactionId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The unique transaction ID used in TeaLeaf PSR tracking"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The trip ID of an existing trip, from /m/api/hotel/trip/create"
                }
              ]
            },
            "description": "Mobile API Hotels Checkout"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96e16a5b-f984-43a4-ac5f-77dde28b7bcd"
            }
          ]
        }
      ]
    }
  ]
}