---
name: Alpha Vantage
x-slug: alpha-vantage
description: Composed of a tight-knit community of researchers, engineers, and business
  professionals, Alpha Vantage Inc. is a leading provider of free APIs for realtime
  and historical data on stocks, physical currencies, and digital/crypto currencies.
  Our success is driven by rigorous research, cutting edge technology, and a disciplined
  focus on democratizing access to data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2018-01-22 at 4.52.35 PM.png
x-kinRank: "8"
x-alexaRank: "160846"
tags: Monthly
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/monthly/master/_listings/alpha-vantage/apis.md
specificationVersion: "0.14"
apis:
- name: Alpha Vantage Digital Currencies Monthly
  x-api-slug: alpha-vantage
  description: This API returns the monthly historical time series for a digital currency
    (e.g., BTC) traded on a specific market (e.g., CNY/Chinese Yuan), refreshed daily
    at midnight (UTC). Prices and volumes are quoted in both the market-specific currency
    and USD.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=DIGITAL_CURRENCY_MONTHLY
  tags: Market Data,Digital Currencies,Monthly,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/monthly/master/_listings/alpha-vantage/queryfunctiondigital-currency-monthly-get-openapi.md
- name: Alpha Vantage
  x-api-slug: alpha-vantage
  description: Composed of a tight-knit community of researchers, engineers, and business
    professionals, Alpha Vantage Inc. is a leading provider of free APIs for realtime
    and historical data on stocks, physical currencies, and digital/crypto currencies.
    Our success is driven by rigorous research, cutting edge technology, and a disciplined
    focus on democratizing access to data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co//
  tags: Monthly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/monthly/master/_listings/alpha-vantage/openapi.md
x-common:
- type: x-command-line-interface
  url: https://www.npmjs.com/package/alpha-vantage-cli
- type: x-documentation
  url: https://www.alphavantage.co/documentation/
- type: x-forum
  url: https://www.alpha-vantage.community/
- type: x-selfservice-registration
  url: https://www.alphavantage.co/support/#api-key
- type: x-support
  url: https://www.alphavantage.co/support/#support
- type: x-terms-of-service
  url: https://www.alphavantage.co/terms_of_service/
- type: x-website
  url: https://www.alphavantage.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---