# Extending Spectral

[Spectral](https://github.com/stoplightio/spectral) is a JSON/YAML linter, with
out of the box support for OpenAPI v2/v3 and AsyncAPI v2. It is becoming
increasingly popular as a tool for defining API style guides that can be used in
reviews and automation. It is very extensible, allowing users to both create
custom rulesets using builtin functions and write custom rules in JavaScript.
This repository is collecting examples of Spectral rulesets and functions in the
wild.

## Stoplight Spectral Documentation

* [Custom Rulesets](https://meta.stoplight.io/docs/spectral/docs/guides/4-custom-rulesets.md)
* [Custom Functions](https://meta.stoplight.io/docs/spectral/docs/guides/5-custom-functions.md)
* [Sharing & Distributing Rulesets](https://meta.stoplight.io/docs/spectral/docs/guides/7-sharing-rulesets.md)
* [Core Functions](https://meta.stoplight.io/docs/spectral/docs/reference/functions.md)

## Custom Rulesets and Functions

* [OpenAPI Community Style Guide](https://github.com/openapi-contrib/style-guides)
  - Collection of custom rulesets including [APIs You Won't Hate](https://github.com/openapi-contrib/style-guides/blob/master/apisyouwonthate.yml), ruleset of "super opinionated HTTP API advice".
* [Nexmo](https://github.com/Nexmo/api-specification)
  - [.spectral.yml](https://github.com/Nexmo/api-specification/blob/master/.spectral.yml)
  - [functions](https://github.com/Nexmo/api-specification/tree/master/functions)
* [Box](https://github.com/box/box-openapi)
  - [.spectral.yml](https://github.com/box/box-openapi/blob/main/.spectral.yml)
  - [functions](https://github.com/box/box-openapi/tree/main/src/spectral)
* [DigitalOcean](https://github.com/digitalocean/openapi)
  - [ruleset.yml](https://github.com/digitalocean/openapi/blob/main/spectral/ruleset.yml)
  - [functions](https://github.com/digitalocean/openapi/tree/main/spectral/functions)
* [Azure](https://github.com/Azure/azure-api-style-guide)
  - [spectral.yaml](https://github.com/Azure/azure-api-style-guide/blob/main/spectral.yaml)
  - [functions](https://github.com/Azure/azure-api-style-guide/tree/main/functions)
* [Using Spectral in Postman](https://learning.postman.com/docs/api-governance/configurable-rules/spectral/)
  * Collection of more than 250 individual Spectral rules shared via [Postman Open Technologies - Governance Rules](https://www.postman.com/postman/workspace/postman-open-technologies-governance-rules/overview) and [linting rules](https://github.com/postman-open-technologies/linting-rules/tree/main/_rules)

## Blog Posts

* [Custom OpenAPI Style Rules with Spectral](https://lornajane.net/posts/2020/custom-openapi-style-rules-with-spectral) by Lorna Jane Mitchell
* [Test Driven Development for Your Spectral Rules, using Jest](https://www.jvt.me/posts/2021/12/22/spectral-jest/) by Jamie Tanna

## Talks

* [The Augmented API Design Reviewer](https://www.youtube.com/watch?v=MAHW5DmM9j4) ([slides](https://speakerdeck.com/arnaudlauret/the-augmented-api-design-reviewer)) by Arnaud Lauret at the API Specifications Conference 2020
