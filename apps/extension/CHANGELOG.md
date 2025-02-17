# chrome-extension

## 11.4.0

### Minor Changes

- f22eef4: Update to latest penumbra-zone packages (uses v10 registry's remote methods)

### Patch Changes

- 144c2fa: Disable the Copy button for the seed phrase until it's revealed
- Updated dependencies [f22eef4]
  - @repo/context@4.4.0
  - @repo/ui@5.3.0

## 11.3.0

### Minor Changes

- Update to latest penumbr-zone & registry deps

### Patch Changes

- Updated dependencies
  - @repo/context@4.3.0
  - @repo/ui@5.2.0

## 11.2.0

### Minor Changes

- f256d9b: Update to latest penumbra-zone pkgs

### Patch Changes

- Updated dependencies [f256d9b]
  - @repo/context@4.2.0
  - @repo/ui@5.1.0

## 11.1.0

### Minor Changes

- No default setting of rpc in onboarding

## 11.0.0

### Major Changes

- 200c492: Update to latest penumbra-zone packages

### Minor Changes

- 8b5a177: fulfill disconnect interface

### Patch Changes

- c04a858: Refactor UI package: sync it with the penumbra-zone/ui and remove unused components
- bc51c5c: save app params
- Updated dependencies [c04a858]
- Updated dependencies [200c492]
  - @repo/ui@5.0.0
  - @repo/context@4.1.0

## 10.0.0

### Major Changes

- e9b0d0d: use imported packages

### Patch Changes

- 93cc701: Update how connection approvals update origin records
- 2287a89: scope init to documentId
- Updated dependencies [e9b0d0d]
  - @repo/context@4.0.0
  - @repo/ui@4.0.0

## 9.1.0

### Minor Changes

- e7d7ffc: 'chrome-extension': Add an onboarding screen for the default frontend selection

  '@penumbra-zone/storage': Remove the MINIFRONT_URL env usages

  '@penumbra-zone/ui': Don't show the image in SelectList.Option component if it is not passed

- 309223c: New registry: rpcs no longer require chain id

### Patch Changes

- adf3a28: Update to june 12 testnet registry
- Updated dependencies [4012c48]
- Updated dependencies [adf3a28]
- Updated dependencies [ab9d743]
- Updated dependencies [282eabf]
- Updated dependencies [0076a1d]
- Updated dependencies [81b9536]
- Updated dependencies [3be0580]
- Updated dependencies [14ba562]
- Updated dependencies [6b06e04]
- Updated dependencies [24c8b4f]
- Updated dependencies [c8e8d15]
- Updated dependencies [24c8b4f]
- Updated dependencies [6ee8222]
- Updated dependencies [e7d7ffc]
  - @penumbra-zone/storage@4.0.0
  - @penumbra-zone/services-context@3.3.0
  - @penumbra-zone/services@4.1.0
  - @penumbra-zone/query@4.1.0
  - @penumbra-zone/types@7.1.0
  - @penumbra-zone/ui@3.4.0
  - @penumbra-zone/protobuf@4.1.0
  - @penumbra-zone/wasm@7.1.0
  - @penumbra-zone/client@6.0.1
  - @penumbra-zone/crypto-web@3.0.10
  - @penumbra-zone/perspective@4.0.1

## 9.0.3

### Patch Changes

- Updated dependencies [8fe4de6]
  - @penumbra-zone/transport-dom@6.0.0
  - @penumbra-zone/perspective@4.0.0
  - @penumbra-zone/protobuf@4.0.0
  - @penumbra-zone/bech32m@5.0.0
  - @penumbra-zone/client@6.0.0
  - @penumbra-zone/wasm@7.0.0
  - @penumbra-zone/services@4.0.3
  - @penumbra-zone/transport-chrome@2.2.2
  - @penumbra-zone/ui@3.3.2
  - @penumbra-zone/query@4.0.2
  - @penumbra-zone/storage@3.4.3
  - @penumbra-zone/types@7.0.1
  - @penumbra-zone/services-context@3.2.3
  - @penumbra-zone/crypto-web@3.0.9

## 9.0.2

### Patch Changes

- Updated dependencies [bb5f621]
- Updated dependencies [8b121ec]
  - @penumbra-zone/types@7.0.0
  - @penumbra-zone/ui@3.3.1
  - @penumbra-zone/transport-dom@5.0.0
  - @penumbra-zone/perspective@3.0.0
  - @penumbra-zone/protobuf@3.0.0
  - @penumbra-zone/bech32m@4.0.0
  - @penumbra-zone/client@5.0.0
  - @penumbra-zone/wasm@6.0.0
  - @penumbra-zone/crypto-web@3.0.8
  - @penumbra-zone/query@4.0.1
  - @penumbra-zone/services@4.0.2
  - @penumbra-zone/services-context@3.2.2
  - @penumbra-zone/storage@3.4.2
  - @penumbra-zone/transport-chrome@2.2.1

## 9.0.1

### Patch Changes

- a22d3a8: Update registry (noble/testnet channel update)
- Updated dependencies [a22d3a8]
  - @penumbra-zone/services-context@3.2.1
  - @penumbra-zone/storage@3.4.1
  - @penumbra-zone/services@4.0.1

## 9.0.0

### Major Changes

- 029eebb: use service definitions from protobuf collection package

### Minor Changes

- 3ea1e6c: update buf types dependencies

### Patch Changes

- Updated dependencies [fc9418c]
- Updated dependencies [120b654]
- Updated dependencies [4f8c150]
- Updated dependencies [029eebb]
- Updated dependencies [029eebb]
- Updated dependencies [e86448e]
- Updated dependencies [3ea1e6c]
  - @penumbra-zone/ui@3.3.0
  - @penumbra-zone/protobuf@2.1.0
  - @penumbra-zone/services@4.0.0
  - @penumbra-zone/query@4.0.0
  - @penumbra-zone/types@6.0.0
  - @penumbra-zone/wasm@5.1.0
  - @penumbra-zone/services-context@3.2.0
  - @penumbra-zone/transport-chrome@2.2.0
  - @penumbra-zone/transport-dom@4.1.0
  - @penumbra-zone/perspective@2.1.0
  - @penumbra-zone/bech32m@3.2.0
  - @penumbra-zone/storage@3.4.0
  - @penumbra-zone/client@4.2.0
  - @penumbra-zone/crypto-web@3.0.7

## 8.1.1

### Patch Changes

- Updated dependencies [d8fef48]
- Updated dependencies [5b80e7c]
  - @penumbra-zone/ui@3.2.0
  - @penumbra-zone/wasm@5.0.1
  - @penumbra-zone/perspective@2.0.1
  - @penumbra-zone/query@3.2.1
  - @penumbra-zone/services@3.2.1
  - @penumbra-zone/services-context@3.1.1
  - @penumbra-zone/storage@3.3.0

## 8.1.0

### Minor Changes

- e47a04e: Update registry to latest (fixes labs + adds starling)
- e4c9fce: Add features to handle auction withdrawals
- 43bf99f: Add a UI to inspect an address; create a <Box /> component

### Patch Changes

- e35c6f7: Deps bumped to latest
- d6b8a23: Update registry
- Updated dependencies [e47a04e]
- Updated dependencies [146b48d]
- Updated dependencies [65677c1]
- Updated dependencies [8ccaf30]
- Updated dependencies [e35c6f7]
- Updated dependencies [cf63b30]
- Updated dependencies [99feb9d]
- Updated dependencies [e4c9fce]
- Updated dependencies [8a3b442]
- Updated dependencies [d6b8a23]
- Updated dependencies [43bf99f]
- Updated dependencies [8ccaf30]
  - @penumbra-zone/services-context@3.1.0
  - @penumbra-zone/storage@3.3.0
  - @penumbra-zone/types@5.0.0
  - @penumbra-zone/wasm@5.0.0
  - @penumbra-zone/perspective@2.0.0
  - @penumbra-zone/services@3.2.0
  - @penumbra-zone/bech32m@3.1.1
  - @penumbra-zone/query@3.2.0
  - @penumbra-zone/ui@3.1.0
  - @penumbra-zone/crypto-web@3.0.6
  - @penumbra-zone/client@4.1.2

## 8.0.0

### Major Changes

- v8.0.0 versioning and manifest

### Patch Changes

- 610a445: update osmosis channel for deimos-8
- Updated dependencies
- Updated dependencies [610a445]
  - @penumbra-zone/ui@3.0.0
  - @penumbra-zone/bech32m@3.1.0
  - @penumbra-zone/query@3.1.0
  - @penumbra-zone/services@3.1.0
  - @penumbra-zone/storage@3.2.0
  - @penumbra-zone/types@4.1.0
  - @penumbra-zone/wasm@4.0.4
  - @penumbra-zone/services-context@3.0.4
  - @penumbra-zone/perspective@1.0.6
  - @penumbra-zone/client@4.1.1
  - @penumbra-zone/crypto-web@3.0.5

## 7.0.3

### Patch Changes

- Updated dependencies [8410d2f]
- Updated dependencies [8410d2f]
  - @penumbra-zone/bech32m@3.0.1
  - @penumbra-zone/client@4.1.0
  - @penumbra-zone/perspective@1.0.5
  - @penumbra-zone/query@3.0.2
  - @penumbra-zone/services@3.0.3
  - @penumbra-zone/storage@3.1.2
  - @penumbra-zone/types@4.0.1
  - @penumbra-zone/ui@2.0.5
  - @penumbra-zone/wasm@4.0.3
  - @penumbra-zone/services-context@3.0.3
  - @penumbra-zone/crypto-web@3.0.4

## 7.0.2

### Patch Changes

- Updated dependencies [fc500af]
- Updated dependencies [6fb898a]
  - @penumbra-zone/transport-dom@4.0.0
  - @penumbra-zone/types@4.0.0
  - @penumbra-zone/services@3.0.2
  - @penumbra-zone/storage@3.1.1
  - @penumbra-zone/client@4.0.1
  - @penumbra-zone/transport-chrome@2.1.2
  - @penumbra-zone/crypto-web@3.0.3
  - @penumbra-zone/perspective@1.0.4
  - @penumbra-zone/query@3.0.1
  - @penumbra-zone/services-context@3.0.2
  - @penumbra-zone/ui@2.0.4
  - @penumbra-zone/wasm@4.0.2

## 7.0.1

### Patch Changes

- Updated dependencies [3148375]
- Updated dependencies [55f31c9]
- Updated dependencies [55f31c9]
- Updated dependencies [fdd4303]
  - @penumbra-zone/transport-dom@3.0.0
  - @penumbra-zone/constants@4.0.0
  - @penumbra-zone/client@4.0.0
  - @penumbra-zone/query@3.0.0
  - @penumbra-zone/types@3.0.0
  - @penumbra-zone/storage@3.1.0
  - @penumbra-zone/bech32m@3.0.0
  - @penumbra-zone/services@3.0.1
  - @penumbra-zone/transport-chrome@2.1.1
  - @penumbra-zone/services-context@3.0.1
  - @penumbra-zone/ui@2.0.3
  - @penumbra-zone/crypto-web@3.0.2
  - @penumbra-zone/perspective@1.0.3
  - @penumbra-zone/wasm@4.0.1

## 7.0.0

### Major Changes

- f23028a: Prax brand integration and renaming

### Minor Changes

- 862283c: Using external registry for ibc chains

### Patch Changes

- Updated dependencies [78ab976]
- Updated dependencies [9f4c112]
- Updated dependencies [862283c]
- Updated dependencies [9f4c112]
  - @penumbra-zone/wasm@4.0.0
  - @penumbra-zone/services@3.0.0
  - @penumbra-zone/constants@3.0.0
  - @penumbra-zone/services-context@3.0.0
  - @penumbra-zone/perspective@1.0.2
  - @penumbra-zone/query@2.0.3
  - @penumbra-zone/storage@3.0.1
  - @penumbra-zone/types@2.0.1
  - @penumbra-zone/ui@2.0.2
  - @penumbra-zone/client@3.0.1
  - @penumbra-zone/crypto-web@3.0.1

## 6.3.0

### Minor Changes

- v6.3 ext updates: loading indicator, portfolio viewing, bug fixes

### Patch Changes

- Updated dependencies [13d0bc5]
- Updated dependencies [b4082b7]
- Updated dependencies [76302da]
  - @penumbra-zone/transport-chrome@2.1.0
  - @penumbra-zone/crypto-web@3.0.0
  - @penumbra-zone/storage@3.0.0
  - @penumbra-zone/query@2.0.2
  - @penumbra-zone/router@2.0.2
  - @penumbra-zone/services@2.0.2

## 6.2.0

### Minor Changes

- 66c2407: v6.2.0 release

### Patch Changes

- Updated dependencies [66c2407]
  - @penumbra-zone/wasm@3.0.0
  - @penumbra-zone/storage@2.0.1
  - @penumbra-zone/perspective@1.0.1
  - @penumbra-zone/query@2.0.1
  - @penumbra-zone/router@2.0.1
  - @penumbra-zone/services@2.0.1
  - @penumbra-zone/ui@2.0.1

## 6.0.0

### Major Changes

- 929d278: barrel imports to facilitate better tree shaking

### Patch Changes

- Updated dependencies [7a1efed]
- Updated dependencies [7a1efed]
- Updated dependencies [8933117]
- Updated dependencies [929d278]
  - @penumbra-zone/client@3.0.0
  - @penumbra-zone/ui@2.0.0
  - @penumbra-zone/wasm@2.0.0
  - @penumbra-zone/constants@2.0.0
  - @penumbra-zone/storage@2.0.0
  - @penumbra-zone/query@2.0.0
  - @penumbra-zone/perspective@1.0.0
  - @penumbra-zone/services@2.0.0
  - @penumbra-zone/bech32@2.0.0
  - @penumbra-zone/crypto-web@2.0.0
  - @penumbra-zone/router@2.0.0
  - @penumbra-zone/types@2.0.0
  - @penumbra-zone/transport-chrome@2.0.0
  - @penumbra-zone/transport-dom@2.0.0

## 5.0.0

### Major Changes

- Initial changest. Git tag v5.0.0 updates.

### Patch Changes

- Updated dependencies
  - @penumbra-zone/client@2.0.0
  - @penumbra-zone/constants@1.1.0
  - @penumbra-zone/transport-dom@1.1.0
  - @penumbra-zone/types@1.1.0
  - @penumbra-zone/query@1.0.2
  - @penumbra-zone/router@1.0.2
  - @penumbra-zone/services@1.0.2
  - @penumbra-zone/storage@1.0.2
  - @penumbra-zone/ui@1.0.2
  - @penumbra-zone/transport-chrome@1.0.1
  - @penumbra-zone/crypto-web@1.0.1
  - @penumbra-zone/wasm@1.0.2
