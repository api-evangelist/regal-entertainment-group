# Regal Entertainment Group

Regal Entertainment Group operates one of the largest motion picture theatre circuits in the United States, with theatres located in densely populated metropolitan markets. Regal provides a developer API portal at [developer.regmovies.com](https://developer.regmovies.com), built on Azure API Management, enabling partners and developers to integrate movie showtimes, theatre listings, ticketing, and loyalty reward capabilities into applications. Regal was acquired by Cineworld Group in 2018 and continues to operate under the Regal brand.

**Website:** [https://www.regmovies.com](https://www.regmovies.com)
**Developer Portal:** [https://developer.regmovies.com](https://developer.regmovies.com)

## APIs

### Regal Cinema API

The Regal Cinema API provides programmatic access to movies, theatre locations, showtimes, ticketing, and Regal Crown Club loyalty features. Partners authenticate via an Azure API Management subscription key obtained from the developer portal.

- **Documentation:** [https://developer.regmovies.com/apis](https://developer.regmovies.com/apis)
- **Sign Up:** [https://developer.regmovies.com/signup/](https://developer.regmovies.com/signup/)

## OpenAPI Specifications

| API | File |
|-----|------|
| Regal Cinema API | [openapi/regal-cinema-openapi.yml](openapi/regal-cinema-openapi.yml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Movie | [json-schema/regal-movie-schema.json](json-schema/regal-movie-schema.json) |
| Showtime | [json-schema/regal-showtime-schema.json](json-schema/regal-showtime-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Movie | [json-structure/regal-movie-structure.json](json-structure/regal-movie-structure.json) |
| Showtime | [json-structure/regal-showtime-structure.json](json-structure/regal-showtime-structure.json) |

## JSON-LD Context

| Context | File |
|---------|------|
| Regal Entertainment Group | [json-ld/regal-entertainment-group-context.jsonld](json-ld/regal-entertainment-group-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| List Movies | [examples/regal-cinema-list-movies-example.json](examples/regal-cinema-list-movies-example.json) |
| List Showtimes | [examples/regal-cinema-list-showtimes-example.json](examples/regal-cinema-list-showtimes-example.json) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Regal Cinema Rules | [rules/regal-cinema-rules.yml](rules/regal-cinema-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Regal Cinema | [capabilities/shared/regal-cinema.yaml](capabilities/shared/regal-cinema.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Cinema Ticketing | Movie discovery, showtime lookup, ticketing, and loyalty integration | [capabilities/cinema-ticketing.yaml](capabilities/cinema-ticketing.yaml) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Regal Entertainment Group | [vocabulary/regal-entertainment-group-vocabulary.yml](vocabulary/regal-entertainment-group-vocabulary.yml) |
