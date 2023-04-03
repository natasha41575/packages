# upstream-test

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] upstream-test`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree upstream-test`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init upstream-test
kpt live apply upstream-test --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
