---
name: USA.Gov Corporate Consumer Contact Information
x-slug: usa-gov-corporate-consumer-contact-information
description: We make the Corporate Consumer Contact listing found in the Consumer
  Action Handbook (PDF) available via a REST API. The API programmatically returns
  all of the information contained in the directory, or you can query the API to return
  just a subset of the available information.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: USA.Gov Corporate Consumer Contact Information
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/usa-gov-corporate-consumer-contact-information/master/_listings/usa-gov-corporate-consumer-contact-information/apis.md
specificationVersion: "0.14"
apis:
- name: USA.Gov Corporate Consumer Contact Information API - Get Contacts
  x-api-slug: contacts-formatcontacts-get
  description: Contacts is a general purpose call that, by default, will return all
    of the corporate directory records. However, you can pass parameters into the
    contacts call that allow you to filter the records returned by the API in powerful
    ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
  baseURL: https://www.usa.gov/api/USAGovAPI/
  tags: Federal Government   GSA, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/usa-gov-corporate-consumer-contact-information/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/usa-gov-corporate-consumer-contact-information/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontacts-get-openapi.md
- name: USA.Gov Corporate Consumer Contact Information API - Get Contact
  x-api-slug: contacts-formatcontactsid-get
  description: The Contact call will let you access an individual corporation's information
    by including its unique identifier in the call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
  baseURL: https://www.usa.gov/api/USAGovAPI/
  tags: Federal Government   GSA, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/usa-gov-corporate-consumer-contact-information/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/usa-gov-corporate-consumer-contact-information/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontactsid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://urban.airship.api.gallery.streamdata.io
- type: x-api-stack
  url: http://usa.gov.corporate.consumer.contact.information.stack.network
- type: x-terms-of-service
  url: https://www.usa.gov/developer-terms-of-service
- type: x-website
  url: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---