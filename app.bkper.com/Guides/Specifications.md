# Specifications
---

The API is built on [Swagger OpenAPI](https://swagger.io/resources/open-api/) and [Google API Discovery](https://developers.google.com/discovery) specifications:

- [Open API json specification](https://bkper.com/openapi.json)
- [Google API discovery document](https://bkper.com/_ah/api/discovery/v1/apis/bkper/v3/rest)

You can use these specification documents to generate client libraries using open source tools such as [OpenAPI generator](https://openapi-generator.tech/) or [Google APIs code generator](https://github.com/google/apis-client-generator), in the language of your choice.

If you want to call the API directly from the browser, you can use the [discovery document with the gapi](https://bkper.com/docs/#rest-api-authentication-javascript).

If you are using **Typescript**, we keep an updated type definitions package on npm you can easily add to your projects for autocomplete and contextual documentation:

- [bkper-api-types](https://www.npmjs.com/package/@bkper/bkper-api-types)