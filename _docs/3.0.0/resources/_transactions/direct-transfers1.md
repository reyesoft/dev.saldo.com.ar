---
resource: direct_transfers1
permalink: /docs/3.0.0/resources/direct_transfers1/
version: 3.0.0
singular: resource
section: Transactions
partOf: t
attributes:
  -
    name: amount
    crud: read
    sortable: 'true'
  -
    name: sent
    crud: 'read, update'
    sortable: 'true'
  -
    name: address
    crud: read
    sortable: 'true'
relationships:
  -
    resource: account
    alias: account
    crud: read
  -
    resource: direct_transfer_actions
    alias: direct_transfer_actions
    crud: read
  -
    resource: direct_transfer_accounts
    alias: direct_transfer_accounts
    crud: read

---
