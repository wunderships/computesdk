# @computesdk/kosa8

## 1.0.5

### Patch Changes

- 6a0b829: Run commands on the sandbox's host directly when the create answer offers it (`direct`), falling back to the API when the host did not run the command.
- 6a0b829: Send requests over one HTTP/2 session per origin, opened when the provider is configured (and to a sandbox's host when it is created), instead of a TLS connection per request; `fetch` remains the fallback.

## 1.0.4

### Patch Changes

- Updated dependencies [1fc7e73]
  - computesdk@4.1.19
  - @computesdk/provider@2.1.25

## 1.0.3

### Patch Changes

- computesdk@4.1.18
- @computesdk/provider@2.1.24

## 1.0.2

### Patch Changes

- 6adbee1: kosa8: measure the exec argument limit in UTF-8 bytes; report exit 124 only when a timed command actually hit its deadline (an early exit 137 is kept); read KOSA8_TEMPLATE and KOSA8_REGION defaults; add SVG logos.

## 1.0.1

### Patch Changes

- 066aa1b: Add kosa8 provider
