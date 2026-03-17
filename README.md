# Manager.io API Schema

Enhanced OpenAPI 3.2.0 schema for the Manager.io API2 with full component support for data attribute mapping.

## Overview

This repository contains a modified version of the Manager.io API schema that includes comprehensive component definitions to facilitate mapping schemas for data attributes.

## Version

API Version: 26.3.12.3199

## Usage

This schema can be used with OpenAPI-compatible tools for:

- API documentation generation
- Client SDK generation
- API testing and validation
- Schema validation

## Example

```bash
# Validate with swagger-cli
npx swagger-cli validate manager-io-api-schema.json

# Generate client with openapi-generator
npx @openapi-generator/cli generate -i manager-io-api-schema.json -g typescript-axios -o ./client
```

## References

- [Manager.io](https://www.manager.io/)
- [Manager.io API Documentation](https://api.manager.io/)
- [OpenAPI Specification](https://spec.openapis.org/oas/v3.2.0)

## License

See the [LICENSE](LICENSE) file for details.