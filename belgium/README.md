# azure

## Description
Something from MS

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] azure`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree azure`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init azure
kpt live apply azure --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
