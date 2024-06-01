---
name: Bunq
description: >-
  We offer mobile banking that makes life easy—wherever, whenever. Join us and
  discover a simple, sustainable, and user-centered way of banking that makes
  everyday finances 100% hassle-free.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/bunq.yml
created: 2023/11/13
modified: 2023/11/13
specificationVersion: '0.16'
tags: []
apis:
  - name: Bunq API
    description: >-
      We offer mobile banking that makes life easy—wherever, whenever. Join us
      and discover a simple, sustainable, and user-centered way of banking that
      makes everyday finances 100% hassle-free.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://doc.bunq.com/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://doc.bunq.com/
      - type: OpenAPI
        url: properties/bunq-openapi-original.yml
    contact:
      - FN: Name
        url: http://example.com
        email: info@example.com
    overlays:
      - type: API Evangelist Ratings
        url: overlays/bunq-openapi-api-evangelist-ratings.yml
      - type: APIs.io Search
        url: overlays/bunq-openapi-search.yml
    aid: bunq:bunq-api
  - name: ' user'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/user-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/user-openapi-search.yml
  - name: ' activity-map-place-public'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/activity-map-place-public-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/activity-map-place-public-openapi-search.yml
  - name: ' activity-map-place-public'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/activity-map-place-public-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/activity-map-place-public-openapi-search.yml
  - name: ' attachment-public'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/attachment-public-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/attachment-public-openapi-search.yml
  - name: ' avatar'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/avatar-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/avatar-openapi-search.yml
  - name: ' device'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/device-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/device-openapi-search.yml
  - name: ' device-server'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/device-server-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/device-server-openapi-search.yml
  - name: ' installation'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/installation-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/installation-openapi-search.yml
  - name: ' user-company'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/user-company-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/user-company-openapi-search.yml
  - name: ' payment-service-provider-credential'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/payment-service-provider-credential-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/payment-service-provider-credential-openapi-search.yml
  - name: ' registry-import-splitwise-csv'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/registry-import-splitwise-csv-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/registry-import-splitwise-csv-openapi-search.yml
  - name: ' sandbox-user-company'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/sandbox-user-company-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/sandbox-user-company-openapi-search.yml
  - name: ' sandbox-user-person'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/sandbox-user-person-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/sandbox-user-person-openapi-search.yml
  - name: ' server-error'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/server-error-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/server-error-openapi-search.yml
  - name: ' session'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/session-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/session-openapi-search.yml
  - name: ' session-server'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/session-server-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/session-server-openapi-search.yml
  - name: ' user-payment-service-provider'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/user-payment-service-provider-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/user-payment-service-provider-openapi-search.yml
  - name: ' user-person'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/user-person-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/user-person-openapi-search.yml    
common:
  - type: Portal
    url: https://developer.bunq.com/en/
  - type: Authentication
    url: https://doc.bunq.com/#/authentication
  - type: Errors
    url: https://doc.bunq.com/#/errors
  - type: Headers
    url: https://doc.bunq.com/#/headers
  - type: Type
    url: https://example.com
  - type: Callbacks
    url: https://doc.bunq.com/#/callbacks
  - type: Pagination
    url: https://doc.bunq.com/#/pagination
  - type: Change Log
    url: https://beta.doc.bunq.com/basics/changelog
  - type: Status
    url: https://status.bunq.com/
  - type: GitHub Organization
    url: https://github.com/bunq
  - type: Postman Collections
    url: https://github.com/bunq/postman/
  - type: Sandbox
    url: https://beta.doc.bunq.com/basics/sandbox
  - type: Blog
    url: https://medium.com/bunq-developers-corner
  - type: FAQ
    url: https://beta.doc.bunq.com/other/faq
  - type: Terms of Service
    url: >-
      https://assets-global.website-files.com/63b43f001c7774d38d5f3a2d/63b43f001c7774ee815f41aa_20200805_terms_bunq_API_EN.pdf
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: bunq
---