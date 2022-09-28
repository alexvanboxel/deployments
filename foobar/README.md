# meetup_1

## Description
Meetup 1

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] meetup_1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree meetup_1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init meetup_1
kpt live apply meetup_1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
