# Safebox Changelog

## 1.1.3

### UI
- Added Font-Awesome 4
- Updated action buttons for components `Clients`, `Sites` and `Accounts`
- Updated components `Clients`, `Sites` and `Accounts` to fit better in responsive

## Clients
- Added fields `address`, `note`, `facebook` and `twitter`

## 1.1.2

### Clients
- The `phone` field is not required anymore

### Accounts
- Fix decrypt when `login`, `password` or `comment` is empty

### Tests
- Fix how database migrations are done between each tests
- Fix `Clients` and `Sites` tests
- Add tests for `Accounts`