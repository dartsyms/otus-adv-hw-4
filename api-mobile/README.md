# org.openapitools.client - Kotlin client library for Recipe Puppy

## Requires

* Kotlin 1.3.50

## Build

```
./gradlew check assemble
```

This runs all tests and packages the library.

## Features/Implementation Notes

* Supports JSON inputs/outputs, File inputs, and Form inputs.
* Supports collection formats for query parameters: csv, tsv, ssv, pipes.
* Some Kotlin and Java types are fully qualified to avoid conflicts with types defined in OpenAPI definitions.


<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://www.recipepuppy.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*RecipeApi* | [**getRecipe**](docs/RecipeApi.md#getrecipe) | **GET** /api/ | Get Recipe


<a name="documentation-for-models"></a>
## Documentation for Models

 - [org.openapitools.client.models.ErrorModel](docs/ErrorModel.md)
 - [org.openapitools.client.models.Recipe](docs/Recipe.md)
 - [org.openapitools.client.models.RecipeList](docs/RecipeList.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
