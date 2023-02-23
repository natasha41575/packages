# config-sync

## Description
Contains CS manifests built from HEAD of main (last updated 2/23/23)

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] config-sync`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree config-sync`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init config-sync
kpt live apply config-sync --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
