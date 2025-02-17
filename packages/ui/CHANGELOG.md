# @penumbra-zone/ui

## 5.3.0

### Minor Changes

- f22eef4: Update to latest penumbra-zone packages (uses v10 registry's remote methods)

## 5.2.0

### Minor Changes

- Update to latest penumbr-zone & registry deps

## 5.1.0

### Minor Changes

- f256d9b: Update to latest penumbra-zone pkgs

## 5.0.0

### Major Changes

- c04a858: Refactor UI package: sync it with the penumbra-zone/ui and remove unused components

### Minor Changes

- 200c492: Update to latest penumbra-zone packages

## 4.0.0

### Major Changes

- e9b0d0d: use imported packages

## 3.4.0

### Minor Changes

- ab9d743: decouple service/rpc init
- 282eabf: Click wallet for max amount
- 0076a1d: add candlestick component
- 24c8b4f: Add ActionDetails.TruncatedText component

### Patch Changes

- 6b06e04: Introduce ZQuery package and use throughout minifront
- 24c8b4f: fix delegation prompting window being too wide
- e7d7ffc: 'chrome-extension': Add an onboarding screen for the default frontend selection

  '@penumbra-zone/storage': Remove the MINIFRONT_URL env usages

  '@penumbra-zone/ui': Don't show the image in SelectList.Option component if it is not passed

- Updated dependencies [ab9d743]
- Updated dependencies [282eabf]
- Updated dependencies [6b06e04]
- Updated dependencies [c8e8d15]
  - @penumbra-zone/types@7.1.0
  - @penumbra-zone/getters@6.1.0
  - @penumbra-zone/perspective@4.0.1

## 3.3.2

### Patch Changes

- Updated dependencies [8fe4de6]
  - @penumbra-zone/perspective@4.0.0
  - @penumbra-zone/bech32m@5.0.0
  - @penumbra-zone/getters@6.0.0
  - @penumbra-zone/types@7.0.1

## 3.3.1

### Patch Changes

- bb5f621: formatAmount() takes new args
- Updated dependencies [bb5f621]
- Updated dependencies [8b121ec]
  - @penumbra-zone/types@7.0.0
  - @penumbra-zone/perspective@3.0.0
  - @penumbra-zone/bech32m@4.0.0
  - @penumbra-zone/getters@5.0.0

## 3.3.0

### Minor Changes

- 120b654: Support estimates of outputs for auctions; redesign the estimate results part of the swap/auction UI
- 3ea1e6c: update buf types dependencies

### Patch Changes

- fc9418c: Fixed a couple bugs, and displayed the auction ID in its details.
- Updated dependencies [120b654]
- Updated dependencies [029eebb]
- Updated dependencies [3ea1e6c]
  - @penumbra-zone/getters@4.1.0
  - @penumbra-zone/types@6.0.0
  - @penumbra-zone/perspective@2.1.0
  - @penumbra-zone/bech32m@3.2.0

## 3.2.0

### Minor Changes

- d8fef48: Update design of DutchAuctionComponent; add filtering to auctions
- 5b80e7c: Add animations to SegmentedPicker

### Patch Changes

- @penumbra-zone/perspective@2.0.1

## 3.1.0

### Minor Changes

- cf63b30: Show swap routes in the UI; extract a <TokenSwapInput /> component.
- e4c9fce: Add features to handle auction withdrawals
- 43bf99f: Add a UI to inspect an address; create a <Box /> component

### Patch Changes

- e35c6f7: Deps bumped to latest
- 8a3b442: optimize animation
- Updated dependencies [146b48d]
- Updated dependencies [8ccaf30]
- Updated dependencies [8ccaf30]
- Updated dependencies [e35c6f7]
- Updated dependencies [cf63b30]
- Updated dependencies [e4c9fce]
- Updated dependencies [8ccaf30]
  - @penumbra-zone/getters@4.0.0
  - @penumbra-zone/types@5.0.0
  - @penumbra-zone/perspective@2.0.0
  - @penumbra-zone/bech32m@3.1.1

## 3.0.0

### Major Changes

- v8.0.0 versioning and manifest

### Patch Changes

- Updated dependencies
  - @penumbra-zone/bech32m@3.1.0
  - @penumbra-zone/types@4.1.0
  - @penumbra-zone/getters@3.0.2
  - @penumbra-zone/perspective@1.0.6

## 2.0.5

### Patch Changes

- Updated dependencies [8410d2f]
  - @penumbra-zone/bech32m@3.0.1
  - @penumbra-zone/getters@3.0.1
  - @penumbra-zone/perspective@1.0.5
  - @penumbra-zone/types@4.0.1

## 2.0.4

### Patch Changes

- Updated dependencies [6fb898a]
  - @penumbra-zone/types@4.0.0
  - @penumbra-zone/perspective@1.0.4

## 2.0.3

### Patch Changes

- Updated dependencies [3148375]
- Updated dependencies [fdd4303]
  - @penumbra-zone/constants@4.0.0
  - @penumbra-zone/getters@3.0.0
  - @penumbra-zone/types@3.0.0
  - @penumbra-zone/bech32m@3.0.0
  - @penumbra-zone/perspective@1.0.3

## 2.0.2

### Patch Changes

- Updated dependencies [862283c]
  - @penumbra-zone/constants@3.0.0
  - @penumbra-zone/perspective@1.0.2
  - @penumbra-zone/getters@2.0.1
  - @penumbra-zone/types@2.0.1

## 2.0.1

### Patch Changes

- @penumbra-zone/perspective@1.0.1

## 2.0.0

### Major Changes

- 929d278: barrel imports to facilitate better tree shaking

### Minor Changes

- 7a1efed: Added warning toast

### Patch Changes

- 8933117: Account for changes to core
- Updated dependencies [929d278]
  - @penumbra-zone/perspective@1.0.0
  - @penumbra-zone/getters@2.0.0
  - @penumbra-zone/bech32@2.0.0
  - @penumbra-zone/types@2.0.0

## 1.0.2

### Patch Changes

- Updated dependencies
  - @penumbra-zone/getters@1.1.0
  - @penumbra-zone/types@1.1.0
