{
  "info": {
    "name": "AXA Assistance Gets the travel certificate details.",
    "_postman_id": "3b572c4c-ec2d-4393-afec-864b55bccc61",
    "description": "Gets the travel certificate details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "88580f11-3993-433c-84ad-a780ef1cfb7f",
          "name": "getSalesV1IndividualTravelCertificatesCertificate_id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "sales/v1/individual/travel/certificates/:certificate_id"
              ],
              "variable": [
                {
                  "id": "certificate_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accept-language",
                "value": "{}",
                "description": "Accepted language, IANA language codification",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the travel certificate details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87dc18e3-db01-440d-99aa-ba6382c902fe"
            }
          ]
        }
      ]
    }
  ]
}