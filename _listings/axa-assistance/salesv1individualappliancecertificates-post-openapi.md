---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Requests the activation of a certificate either to cover an
    appliance purchased or to extend the warranty period of an appliance purchased.
    At least one product_criteria has to be specified to identify the product to which
    to subscribe. This endpoint
  description: Requests the activation of a certificate either to cover an appliance
    purchased or to extend the warranty period of an appliance purchased. At least
    one product_criteria has to be specified to identify the product to which to subscribe.
    This endpoint
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
  /insurance/vexp/appliance/claims:
    post:
      summary: Requests to create a claim related to an appliance.
      description: Requests to create a claim related to an appliance.
      operationId: postInsuranceVexpApplianceClaims
      x-api-path-slug: insurancevexpapplianceclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - toappliance.
  /insurance/vexp/car_rental/claims:
    post:
      summary: Requests to create a claim related to a car rental.
      description: Requests to create a claim related to a car rental.
      operationId: postInsuranceVexpCar_rentalClaims
      x-api-path-slug: insurancevexpcar-rentalclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tocar
      - rental.
  /insurance/vexp/corporate_liability/claims:
    post:
      summary: Requests to create a claim related to a corporate liability.
      description: Requests to create a claim related to a corporate liability.
      operationId: postInsuranceVexpCorporate_liabilityClaims
      x-api-path-slug: insurancevexpcorporate-liabilityclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tocorporate
      - liability.
  /insurance/vexp/delayed_luggage/claims:
    post:
      summary: Requests to create a claim related to a delayed luggage.
      description: Requests to create a claim related to a delayed luggage.
      operationId: postInsuranceVexpDelayed_luggageClaims
      x-api-path-slug: insurancevexpdelayed-luggageclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - todelayed
      - luggage.
  /insurance/vexp/delayed_trip/claims:
    post:
      summary: Requests to create a claim related to a delayed trip.
      description: Requests to create a claim related to a delayed trip.
      operationId: postInsuranceVexpDelayed_tripClaims
      x-api-path-slug: insurancevexpdelayed-tripclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - todelayed
      - trip.
  /insurance/vexp/lost_baggage/claims:
    post:
      summary: Requests to create a claim related to a lost baggage.
      description: Requests to create a claim related to a lost baggage.
      operationId: postInsuranceVexpLost_baggageClaims
      x-api-path-slug: insurancevexplost-baggageclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tolost
      - baggage.
  /insurance/vexp/missed_flight/claims:
    post:
      summary: Requests to create a claim related to a missed flight.
      description: Requests to create a claim related to a missed flight.
      operationId: postInsuranceVexpMissed_flightClaims
      x-api-path-slug: insurancevexpmissed-flightclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tomissed
      - flight.
  /insurance/vexp/price_protection/claims:
    post:
      summary: Requests to create a claim related to a price protection.
      description: Requests to create a claim related to a price protection.
      operationId: postInsuranceVexpPrice_protectionClaims
      x-api-path-slug: insurancevexpprice-protectionclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - toprice
      - protection.
  /insurance/vexp/stolen_cash/claims:
    post:
      summary: Requests to create a claim related to a stolen cash.
      description: Requests to create a claim related to a stolen cash.
      operationId: postInsuranceVexpStolen_cashClaims
      x-api-path-slug: insurancevexpstolen-cashclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tostolen
      - cash.
  /insurance/vexp/travel_accident/claims:
    post:
      summary: Requests to create a claim related to a travel accident.
      description: Requests to create a claim related to a travel accident.
      operationId: postInsuranceVexpTravel_accidentClaims
      x-api-path-slug: insurancevexptravel-accidentclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totravel
      - accident.
  /insurance/vexp/trip/claims:
    post:
      summary: Requests to create a claim related to a trip.
      description: Requests to create a claim related to a trip.
      operationId: postInsuranceVexpTripClaims
      x-api-path-slug: insurancevexptripclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totrip.
  /insurance/vexp/trip_cancellation/claims:
    post:
      summary: Requests to create a claim related to a trip cancellation.
      description: Requests to create a claim related to a trip cancellation.
      operationId: postInsuranceVexpTrip_cancellationClaims
      x-api-path-slug: insurancevexptrip-cancellationclaims-post
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
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totrip
      - cancellation.
  /sales/v1/individual/appliance/certificates:
    post:
      summary: Requests the activation of a certificate either to cover an appliance
        purchased or to extend the warranty period of an appliance purchased. At least
        one product_criteria has to be specified to identify the product to which
        to subscribe. This endpoint
      description: Requests the activation of a certificate either to cover an appliance
        purchased or to extend the warranty period of an appliance purchased. At least
        one product_criteria has to be specified to identify the product to which
        to subscribe. This endpoint
      operationId: postSalesV1IndividualApplianceCertificates
      x-api-path-slug: salesv1individualappliancecertificates-post
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
      - Insurance
      - RequestAssistance
      - the
      - activation
      - ofcertificate
      - either
      - to
      - coverappliance
      - purchasedto
      - extend
      - the
      - warranty
      - period
      - ofappliance
      - purchased.
      - At
      - leastproduct_criteria
      - haAssistance
      - to
      - be
      - specified
      - to
      - identify
      - the
      - product
      - to
      - which
      - to
      - subscribe.
      - ThiAssistance
      - endpoint
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