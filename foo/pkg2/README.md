# foo/pkg2

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] foo/pkg2`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree foo/pkg2`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init foo/pkg2
kpt live apply foo/pkg2 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
