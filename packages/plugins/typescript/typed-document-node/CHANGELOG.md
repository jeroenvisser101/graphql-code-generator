# @graphql-codegen/typed-document-node

## 1.18.1

### Patch Changes

- 1183d173: Bump all packages to resolve issues with shared dependencies
- Updated dependencies [1183d173]
  - @graphql-codegen/visitor-plugin-common@1.17.20
  - @graphql-codegen/plugin-helpers@1.18.2

## 1.18.0

### Minor Changes

- bd3bd296: Improve DocumentNode optimizations, to reduce bundle size when consumed as pre-compiled

### Patch Changes

- Updated dependencies [99819bf1]
- Updated dependencies [c3b59e81]
  - @graphql-codegen/visitor-plugin-common@1.17.19

## 1.17.10

### Patch Changes

- 3e3941b9: Avoid printing imports when there are no operations
- Updated dependencies [612e5e52]
- Updated dependencies [9f2a4e2f]
- Updated dependencies [0f35e775]
- Updated dependencies [eaf45d1f]
  - @graphql-codegen/visitor-plugin-common@1.17.17
  - @graphql-codegen/plugin-helpers@1.18.1

## 1.17.9

### Patch Changes

- 1d7c6432: Bump all packages to allow "^" in deps and fix compatibility issues
- 1d7c6432: Bump versions of @graphql-tools/ packages to fix issues with loading schemas and SDL comments
- Updated dependencies [1d7c6432]
- Updated dependencies [1d7c6432]
  - @graphql-codegen/visitor-plugin-common@1.17.13
  - @graphql-codegen/plugin-helpers@1.17.8

## 1.17.8

### Patch Changes

- 4266a15f: Allow this plugin to work with `documentMode: graphqlTag` correctly.

  Added validation for preventing `documentMode: string` because it's not supported in this plugin.

- Updated dependencies [4266a15f]
  - @graphql-codegen/visitor-plugin-common@1.17.12
