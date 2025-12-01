# [Group] _storage account_

Manage storage accounts.

## Subgroups

- [migration](/Commands/storage/account/migration/readme.md)
: Manage Storage Account Migration

- [network-security-perimeter-configuration](/Commands/storage/account/network-security-perimeter-configuration/readme.md)
: Manage Network Security Perimeter Configuration

- [task-assignment](/Commands/storage/account/task-assignment/readme.md)
: Manage storage account task assignment.

## Commands

- [create](/Commands/storage/account/_create.md)
: Create creates a new storage account with the specified parameters. If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated. If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.

- [delete](/Commands/storage/account/_delete.md)
: Delete a storage account in Microsoft Azure.

- [file-service-usage](/Commands/storage/account/_file-service-usage.md)
: Get the usage of file service in storage account including account limits, file share limits and constants used in recommendations and bursting formula.

- [list](/Commands/storage/account/_list.md)
: List all the storage accounts available under the subscription. Note that storage keys are not returned; use the ListKeys operation for this.

- [show](/Commands/storage/account/_show.md)
: Get the properties for the specified storage account including but not limited to name, SKU name, location, and account status. The ListKeys operation should be used to retrieve storage keys.

- [update](/Commands/storage/account/_update.md)
: Update creates a new storage account with the specified parameters. If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated. If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.
