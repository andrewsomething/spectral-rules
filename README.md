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
  - Collection of custom rulesets including [APIs You Won't Hate](https://github.com/openapi-contrib/style-guides), "a super opinionated HTTP API advice".
* [Nexmo](https://github.com/Nexmo/api-specification)
  - [.spectral.yml](https://github.com/Nexmo/api-specification/blob/master/.spectral.yml)
  - [functions](https://github.com/Nexmo/api-specification/tree/master/functions)
* [Box](https://github.com/box/box-openapi)
  - [.spectral.yml](https://github.com/box/box-openapi/blob/main/.spectral.yml)
  - [functions](https://github.com/box/box-openapi/tree/main/src/spectral)

## Blog Posts

* [Custom OpenAPI Style Rules with Spectral](https://lornajane.net/posts/2020/custom-openapi-style-rules-with-spectral) by Lorna Jane Mitchell
