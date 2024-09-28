---
name: National Weather Service
description: >-
  The National Weather Service (NWS) API allows developers access to critical
  forecasts, alerts, and observations, along with other weather data. The API
  was designed with a cache-friendly approach that expires content based upon
  the information life cycle. The API is based upon of JSON-LD to promote
  machine data discovery.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/api-search/us-federal-government/main/_apis/national-weather-service/apis.md
created: 2024/01/01
modified: 2024/01/01
specificationVersion: '0.16'
tags: []
apis:
  - name: National Weather Service API
    description: >-
      The National Weather Service (NWS) API allows developers access to
      critical forecasts, alerts, and observations, along with other weather
      data. The API was designed with a cache-friendly approach that expires
      content based upon the information life cycle. The API is based upon of
      JSON-LD to promote machine data discovery.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://www.weather.gov/documentation/services-web-api
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://www.weather.gov/documentation/services-web-api
    overlays: []
    aid: national-weather-service:national-weather-service-api
common:
  - type: Property
    url: https://example.com
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: national-weather-service
---