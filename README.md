# Patreon OpenAPI

This repository contains a preview of the [OpenAPI 3.1 specification](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.1.0.md) for [Patreons's API](https://docs.patreon.com/). Currently, the spec is only available for the API version [v2](https://docs.patreon.com/#apiv2-oauth).

> [!WARNING] Unofficial specification
> This repository is not created, maintained or associated in any way with Patreon. Both specifications are made from the public documented API and are subject to breaking changes without notice if Patreon updates the public API.

## Usage

### Spec Files

Two versions of the spec are included—the standard spec and the preview spec:

- [`openapi.json`](specs/openapi.json) is the standard spec that contains the documented, public API.
- [`openapi_preview.json`](specs/openapi_preview.json) is the preview spec which contains unstable and/or undocumented API features. **This should not be considered stable** or used in production environments.

### Documentation

The public OpenAPI specification is also available on the [documentation of `patreon-api.ts`](https://patreon-api.pages.dev/api/).

<!-- TODO: -->
<!-- ### Integrating with Postman -->

## Contributing

OpenAPI spec contents are automatically generated by the [`patreon-api.ts`](https://github.com/ghostrider-05/patreon-api.ts) library.

For bug fixes or improvements for the OpenAPI spec, you can [open an issue](https://github.com/ghostrider-05/patreon-api-spec/issues).

## Known issues

TODO: add known issues

## License

[MIT](https://github.com/ghostrider-05/patreon-api.ts/blob/main/LICENSE)