# Vite Plugin OpenSearch

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

OpenSearch discovery integration for Vite applications. This plugin allows your Vite-powered site to be added as a search engine in browsers via the OpenSearch protocol.

## Features

- 🔍 Auto-generate `opensearch.xml` from configuration
- 🎨 Support for custom `opensearch.xml` files
- 🚀 Auto-serve OpenSearch description at `/opensearch.xml`
- 📝 Automatic HTML head injection with OpenSearch link tag
- ⚙️ Full TypeScript support with comprehensive configuration options
- 🎯 Sensible defaults for all required fields
- 📋 Support for all OpenSearch specification fields

## Resources

- [OpenSearch Protocol Specification](https://opensearchfoundation.org/)
- [Browser OpenSearch Implementation Guide](https://developer.mozilla.org/en-US/docs/Web/OpenSearch)

## Contribution

<details>
  <summary>Local development</summary>
  
  ```bash
  # Install dependencies
  pnpm install

  # Generate type stubs
  pnpm run dev:prepare

  # Develop with the playground
  pnpm run dev

  # Build the playground
  pnpm run dev:build

  # Run ESLint
  pnpm run lint

  # Run Vitest
  pnpm run test
  pnpm run test:watch

  # Release new version
  pnpm run release
  ```

</details>


<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-opensearch/latest.svg?style=flat&colorA=020420&colorB=00DC82
[npm-version-href]: https://npmjs.com/package/nuxt-opensearch
[npm-downloads-src]: https://img.shields.io/npm/dm/nuxt-opensearch.svg?style=flat&colorA=020420&colorB=00DC82
[npm-downloads-href]: https://npm.chart.dev/nuxt-opensearch
[license-src]: https://img.shields.io/npm/l/nuxt-opensearch.svg?style=flat&colorA=020420&colorB=00DC82
[license-href]: https://npmjs.com/package/nuxt-opensearch
[nuxt-src]: https://img.shields.io/badge/Nuxt-020420?logo=nuxt
[nuxt-href]: https://nuxt.com

