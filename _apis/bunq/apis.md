---
name: Bunq
description: >-
  We offer mobile banking that makes life easy—wherever, whenever. Join us and
  discover a simple, sustainable, and user-centered way of banking that makes
  everyday finances 100% hassle-free.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/api-search/banking/main/_apis/bunq/apis.md
created: 2023/11/13
modified: 2023/11/13
specificationVersion: '0.16'
tags: []
apis:
  - name: Bunq Activity Map Place API
    description: Managing activity map for a user account.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-activity-map-place-public-itemid-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-activity-map-place-public-itemid-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-activity-map-place-public-itemid-openapi-api-evangelist-ratings.yml
    baseURL: https://public-api.sandbox.bunq.com/
    humanURL: https://doc.bunq.com/#/activity-map-place-public
    score: 85
    aid: bunq:bunq-activity-map-place-api
  - name: Bunq Transaction Categories API
    description: Manage additional information transactional categories.
    tags:
      - Additional
      - Categories
      - Information
      - Transactions
      - Users
      - Defined
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-additional-transaction-information-category-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-additional-transaction-information-category-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-additional-transaction-information-category-openapi-api-evangelist-ratings.yml
    baseURL: https://public-api.sandbox.bunq.com/
    humanURL: https://doc.bunq.com/#/additional-transaction-information-category
    score: 156
    aid: bunq:bunq-transaction-categories-api
  - name: Bunq Monetary Account API
    description: Managing different types of monetary accounts.
    tags:
      - Accounts
      - Actions
      - Adyen
      - Allocate
      - Attachments
      - Auto
      - Bank
      - Batches
      - Cards
      - Cloud
      - Content
      - Conversions
      - Currencies
      - Customers
      - Definitions
      - Draft
      - Eal
      - Events
      - Exports
      - External
      - Filter
      - Fundraiser
      - Ideal
      - Inquiries
      - Instances
      - Invite
      - Invoices
      - Items
      - Joint
      - Mastercard
      - Merchants
      - Monetary
      - Notes
      - Notifications
      - Payments
      - Quotes
      - Responses
      - Results
      - Savings
      - Schedules
      - Services
      - Share
      - Statements
      - Switch
      - Tabs
      - Text
      - Transactions
      - URL
      - Users
      - Whitelist
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-monetary-account-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-openapi-search.yml
    humanURL: https://doc.bunq.com/#/monetary-account
    baseURL: https://public-api.sandbox.bunq.com/
    aid: bunq:bunq-monetary-account-api
  - name: Bunq Attachments API
    description: An API for managing attachments associated with a Bunq account.
    tags:
      - Attachments
      - Items
      - Users
      - Content
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-attachment-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-attachment-openapi-search.yml
    humanURL: https://doc.bunq.com/#/attachment
    baseURL: https://public-api.sandbox.bunq.com/
    aid: bunq:bunq-attachments-api
  - name: Bunq Avatar API
    description: >-
      Avatars are public images used to represent you or your company. Avatars
      are used to represent users, monetary accounts and cash registers. Avatars
      cannot be deleted, only replaced. Avatars can be updated after uploading
      the image you would like to use through AttachmentPublic. Using the
      attachment_public_uuid which is returned you can update your Avatar.
      Avatars used for cash registers and company accounts will be reviewed by
      bunq.
    tags:
      - Avatars
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-avatar--openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-avatar--openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-avatar--openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/avatar
    aid: bunq:bunq-avatar-api
    score: 86
  - name: Bunq Billing Contract Subscription API
    description: Manage all subscription billing contract for the authenticated user.
    tags:
      - Billing
      - Contracts
      - Subscriptions
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-billing-contract-subscription-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-billing-contract-subscription-openapi-search.yml
    humanURL: >-
      https://doc.bunq.com/#/billing-contract-subscription/List_all_BillingContractSubscription_for_User
    aid: bunq:bunq-billing-contract-subscription-api
  - name: Bunq Fundraiser Profile API
    description: The /me profile for the Bunq user.
    tags:
      - Fundraiser
      - Items
      - Profiles
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-bunqme-fundraiser-profile-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-bunqme-fundraiser-profile-openapi-search.yml
    humanURL: >-
      https://doc.bunq.com/#/bunqme-fundraiser-profile/READ_BunqmeFundraiserProfile_for_User
    aid: bunq:bunq-fundraiser-profile-api
  - name: Bunq Oauth Client API
    description: For managing OAuth clients through an API.
    tags:
      - Callback
      - Clients
      - Items
      - OAuth
      - URL
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-oauth-client-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-oauth-client-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-oauth-client-openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/
    aid: bunq:bunq-oauth-client-api
    score: 696
  - name: Bunq Card API
    description: Managing cards and transactions made via cards.
    tags:
      - Cards
      - Items
      - Users
      - Batches
      - Replace
      - Credit
      - Debit
      - Names
      - Content
      - Exports
      - Statements
      - CSV
      - PDF
      - Generated
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-card-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-card-openapi-search.yml
    humanURL: https://doc.bunq.com/#/card
    aid: bunq:bunq-card-api
  - name: Bunq Certificate Pinning API
    description: Managing the pinned certificates for a user.
    tags:
      - Certificates
      - Pinned
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-certificate-pinned-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-certificate-pinned-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-certificate-pinned-openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/certificate-pinned
    aid: bunq:bunq-certificate-pinning-api
    score: 292
  - name: Bunq Challenge Request API
    description: Managing the challenge requests for a user.
    tags:
      - Challenges
      - Items
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-challenge-request-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-challenge-request-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-challenge-request-openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/challenge-request
    aid: bunq:bunq-challenge-request-api
    score: 168
  - name: Bunq Company API
    description: Managing details of an accounts company information.
    tags:
      - Companies
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-company-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-company-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-user-userid-company-openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/company
    aid: bunq:bunq-company-api
    score: 299
  - name: Bunq Confirmation Of Funds API
    description: Used to confirm availability of funds on an account.
    tags:
      - Confirmation
      - Funds
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-confirmation-of-funds-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-confirmation-of-funds-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-confirmation-of-funds-openapi-api-evangelist-ratings.yml
    humanURL: >-
      https://doc.bunq.com/#/confirmation-of-funds/CREATE_ConfirmationOfFunds_for_User
    aid: bunq:bunq-confirmation-of-funds-api
    score: 85
  - name: Bunq Chat Conversation API
    description: Managing the chat conversations for a user account.
    tags:
      - Attachments
      - Chat
      - Content
      - Conversations
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-chat-conversation-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-chat-conversation-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-chat-conversation-openapi-api-evangelist-ratings.yml
    humanURL: >-
      https://doc.bunq.com/#/content/List_all_Content_for_User_ChatConversation_Attachment
    aid: bunq:bunq-chat-conversation-api
    score: 106
  - name: Bunq Attachment Content API
    description: Used to manage the attachment content for an A/PI.
    tags:
      - Attachments
      - Content
      - Public
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-attachment-public-attachment-publicuuid-content-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-attachment-public-attachment-publicuuid-content-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-attachment-public-attachment-publicuuid-content-openapi-api-evangelist-ratings.yml
    humanURL: https://doc.bunq.com/#/content
    aid: bunq:bunq-attachment-content-api
    score: 87
  - name: Bunq Export Annual Overview API
    description: Used to retrieve the raw content of an annual overview.
    tags:
      - Annual
      - Content
      - Exports
      - Overview
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-export-annual-overview-openapi-original.yml
      - type: Documentation
        url: https://doc.bunq.com/
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-export-annual-overview-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-export-annual-overview-openapi-api-evangelist-ratings.yml
    humanURL: >-
      https://doc.bunq.com/#/content/List_all_Content_for_User_ExportAnnualOverview
    aid: bunq:bunq-export-annual-overview-api
    score: 370
  - name: Bunq User Credential Password Ip API
    description: Needs description.
    tags:
      - Credentials
      - IP
      - Items
      - Password
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-credential-password-ip-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-credential-password-ip-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-credential-password-ip-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-credential-password-ip-api
    score: 484
  - name: Bunq User Currency Cloud Beneficiary API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-currency-cloud-beneficiary-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-currency-cloud-beneficiary-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-currency-cloud-beneficiary-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-currency-cloud-beneficiary-api
    score: 294
  - name: Bunq Device API
    description: Needs description.
    tags:
      - Device
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-device--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-device--openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-device--openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-device-api
    score: 85
  - name: Bunq Device Server API
    description: Needs description.
    tags:
      - Device
      - Items
      - Servers
    properties:
      - type: OpenAPI
        url: properties/bunq-device-server--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-device-server--openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-device-server--openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-device-server-api
    score: 85
  - name: Bunq User Event API
    description: Needs description.
    tags:
      - Events
      - Items
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-event-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-event-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-user-userid-event-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-event-api
    score: 164
  - name: Bunq User Feature Announcement API
    description: Needs description.
    tags:
      - Announcement
      - Feature
      - Items
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-feature-announcement-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-feature-announcement-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-feature-announcement-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-feature-announcement-api
    score: 95
  - name: Bunq User Insight Preference Date API
    description: Needs description.
    tags:
      - Dates
      - Insights
      - Preferences
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-insight-preference-date-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-insight-preference-date-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-insight-preference-date-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-insight-preference-date-api
    score: 86
  - name: Bunq User Insights API
    description: Needs description.
    tags:
      - Insights
      - Users
      - Search
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-insights-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-insights-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-user-userid-insights-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-insights-api
    score: 154
  - name: Bunq Installation API
    description: Needs description.
    tags:
      - Installations
      - Items
      - Keys
      - Public
      - Servers
    properties:
      - type: OpenAPI
        url: properties/bunq-installation--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-installation--openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-installation--openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-installation-api
    score: 153
  - name: Bunq User Invoice API
    description: Needs description.
    tags:
      - Invoices
      - Users
      - Items
      - Content
      - PDF
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-invoice-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-invoice-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-user-userid-invoice-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-invoice-api
    score: 241
  - name: Bunq User Legal Name API
    description: Needs description.
    tags:
      - Legal
      - Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-legal-name-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-legal-name-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-legal-name-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-legal-name-api
    score: 86
  - name: Bunq User Limit API
    description: Needs description.
    tags:
      - Limits
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-limit-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-limit-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bunq-user-userid-limit-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-limit-api
    score: 86
  - name: Bunq User Monetary Account Bank API
    description: Needs description.
    tags:
      - Accounts
      - Bank
      - Monetary
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-monetary-account-bank-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-bank-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-monetary-account-bank-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-monetary-account-bank-api
    score: 299
  - name: Bunq User Monetary Account Card API
    description: Needs description.
    tags:
      - Accounts
      - Cards
      - Items
      - Monetary
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-monetary-account-card-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-card-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-monetary-account-card-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-monetary-account-card-api
    score: 236
  - name: Bunq User Monetary Account External API
    description: Needs description.
    tags:
      - Accounts
      - External
      - Monetary
      - Users
      - Items
      - Savings
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-monetary-account-external-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-external-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-monetary-account-external-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-monetary-account-external-api
    humanURL: https://doc.bunq.com/#/monetary-account-external
    score: 580
  - name: Bunq User Monetary Account Joint API
    description: Needs description.
    tags:
      - Accounts
      - Joint
      - Monetary
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-monetary-account-joint-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-joint-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-monetary-account-joint-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-monetary-account-joint-api
    score: 300
  - name: Bunq User Monetary Account Savings API
    description: Needs description.
    tags:
      - Accounts
      - Monetary
      - Savings
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-monetary-account-savings-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-monetary-account-savings-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/bunq-user-userid-monetary-account-savings-openapi-api-evangelist-ratings.yml
    aid: bunq:bunq-user-monetary-account-savings-api
    score: 301
  - name: Bunq User Company User Company Name API
    description: Needs description.
    tags:
      - Companies
      - Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-company-user-companyid-name-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-company-user-companyid-name-openapi-search.yml
    aid: bunq:bunq-user-company-user-company-name-api
  - name: Bunq User Notification Filter Email API
    description: Needs description.
    tags:
      - Emails
      - Filter
      - Notifications
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-notification-filter-email-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-notification-filter-email-openapi-search.yml
    aid: bunq:bunq-user-notification-filter-email-api
  - name: Bunq User Notification Filter Failure API
    description: Needs description.
    tags:
      - Failure
      - Filter
      - Notifications
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-notification-filter-failure-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-notification-filter-failure-openapi-search.yml
    aid: bunq:bunq-user-notification-filter-failure-api
  - name: Bunq User Notification Filter Push API
    description: Needs description.
    tags:
      - Filter
      - Notifications
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-notification-filter-push-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-notification-filter-push-openapi-search.yml
    aid: bunq:bunq-user-notification-filter-push-api
  - name: Bunq User Notification Filter Url API
    description: Needs description.
    tags:
      - Filter
      - Notifications
      - URL
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-notification-filter-url-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-notification-filter-url-openapi-search.yml
    aid: bunq:bunq-user-notification-filter-url-api
  - name: Bunq User Payment Auto Allocate API
    description: Needs description.
    tags:
      - Allocate
      - Auto
      - Payments
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-payment-auto-allocate-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-payment-auto-allocate-openapi-search.yml
    aid: bunq:bunq-user-payment-auto-allocate-api
  - name: Bunq Payment Service Provider Credential API
    description: Needs description.
    tags:
      - Credentials
      - Er
      - Items
      - Payments
      - Prov
      - Providers
      - Services
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-payment-service-provider-credential--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-payment-service-provider-credential--openapi-search.yml
    aid: bunq:bunq-payment-service-provider-credential-api
  - name: Bunq User Payment Service Provider Draft Payment API
    description: Needs description.
    tags:
      - Draft
      - Er
      - Payments
      - Prov
      - Providers
      - Services
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-payment-service-provider-draft-payment-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-payment-service-provider-draft-payment-openapi-search.yml
    aid: bunq:bunq-user-payment-service-provider-draft-payment-api
  - name: Bunq User Payment Service Provider Issuer Transaction API
    description: Needs description.
    tags:
      - Er
      - Issuer
      - Payments
      - Prov
      - Providers
      - Services
      - Transactions
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-payment-service-provider-issuer-transaction-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-payment-service-provider-issuer-transaction-openapi-search.yml
    aid: bunq:bunq-user-payment-service-provider-issuer-transaction-api
  - name: Bunq Registry Import Splitwise Csv API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-registry-import-splitwise-csv--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-registry-import-splitwise-csv--openapi-search.yml
    aid: bunq:bunq-registry-import-splitwise-csv-api
  - name: Bunq User Registry API
    description: Needs description.
    tags:
      - Registries
      - Settlements
      - Users
      - Items
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-registry-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-registry-openapi-search.yml
    aid: bunq:bunq-user-registry-api
  - name: Bunq Sandbox User Company API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-sandbox-user-company--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-sandbox-user-company--openapi-search.yml
    aid: bunq:bunq-sandbox-user-company-api
  - name: Bunq Sandbox User Person API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-sandbox-user-person--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-sandbox-user-person--openapi-search.yml
    aid: bunq:bunq-sandbox-user-person-api
  - name: Bunq User Schedule API
    description: Needs description.
    tags:
      - Schedules
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-schedule-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-schedule-openapi-search.yml
    aid: bunq:bunq-user-schedule-api
  - name: Bunq Server Error API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-server-error--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-server-error--openapi-search.yml
    aid: bunq:bunq-server-error-api
  - name: Bunq Installation Installation Server Public Key API
    description: Needs description.
    tags:
      - Installations
      - Keys
      - Public
      - Servers
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-installation-installationid-server-public-key-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-installation-installationid-server-public-key-openapi-search.yml
    aid: bunq:bunq-installation-installation-server-public-key-api
  - name: Bunq Session Item API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-session-itemid--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-session-itemid--openapi-search.yml
    aid: bunq:bunq-session-item-api
  - name: Bunq Session Server API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-session-server--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-session-server--openapi-search.yml
    aid: bunq:bunq-session-server-api
  - name: Bunq User Share Invite Monetary Account Response API
    description: Needs description.
    tags:
      - Accounts
      - Invite
      - Items
      - Monetary
      - Share
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-share-invite-monetary-account-response-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/bunq-user-userid-share-invite-monetary-account-response-openapi-search.yml
    aid: bunq:bunq-user-share-invite-monetary-account-response-api
  - name: Bunq User Token Qr Request Eal API
    description: Needs description.
    tags:
      - Ideal
      - Tokens
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-token-qr-request-ideal-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-token-qr-request-ideal-openapi-search.yml
    aid: bunq:bunq-user-token-qr-request-eal-api
  - name: Bunq User Token Qr Request Sofort API
    description: Needs description.
    tags:
      - Tokens
      - Users
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-userid-token-qr-request-sofort-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-token-qr-request-sofort-openapi-search.yml
    aid: bunq:bunq-user-token-qr-request-sofort-api
  - name: Bunq User Transferwise Currency API
    description: Needs description.
    tags:
      - Currencies
      - Transferwise
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-transferwise-currency-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-transferwise-currency-openapi-search.yml
    aid: bunq:bunq-user-transferwise-currency-api
  - name: Bunq User Transferwise Quote API
    description: Needs description.
    tags:
      - Quotes
      - Transferwise
      - Users
      - Items
      - Temporary
      - Recipient
      - Requirements
      - Transfers
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-transferwise-quote-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-transferwise-quote-openapi-search.yml
    aid: bunq:bunq-user-transferwise-quote-api
  - name: Bunq User Transferwise User API
    description: Needs description.
    tags:
      - Transferwise
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-transferwise-user-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-transferwise-user-openapi-search.yml
    aid: bunq:bunq-user-transferwise-user-api
  - name: Bunq User Tree Progress API
    description: Needs description.
    tags:
      - Progress
      - Trees
      - Users
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-tree-progress-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-tree-progress-openapi-search.yml
    aid: bunq:bunq-user-tree-progress-api
  - name: Bunq User Item API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-user-itemid--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-itemid--openapi-search.yml
    aid: bunq:bunq-user-item-api
  - name: Bunq User Company Item API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-user-company-itemid--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-company-itemid--openapi-search.yml
    aid: bunq:bunq-user-company-item-api
  - name: Bunq User Payment Service Provider Item API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/bunq-user-payment-service-provider-itemid--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-payment-service-provider-itemid--openapi-search.yml
    aid: bunq:bunq-user-payment-service-provider-item-api
  - name: Bunq User Person Item API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/bunq-user-person-itemid--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-person-itemid--openapi-search.yml
    aid: bunq:bunq-user-person-item-api
  - name: Bunq User Whitelist Sdd API
    description: Needs description.
    tags:
      - Items
      - Users
      - Whitelist
      - Recurring
    properties:
      - type: OpenAPI
        url: properties/bunq-user-userid-whitelist-sdd-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/bunq-user-userid-whitelist-sdd-openapi-search.yml
    aid: bunq:bunq-user-whitelist-sdd-api
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
score: 1805
---