---
resource: accounts
permalink: /docs/3.0.0/resources/accounts/
version: 3.0.0
singular: resource
section: Accounts
partOf: u
attributes:
  -
    name: address
    crud: 'create, read, update'
  -
    name: deleted_at
    crud: 'create, read, update'
    filter: DeletedFilter
    sortable: 'true'
relationships:
  -
    resource: system
    alias: system
    crud: 'create, read, update'
  -
    resource: account_detail
    alias: account_detail
    crud: 'create, read, update'
  -
    resource: send_transactions
    alias: send_transactions
    crud: 'create, read, update'
  -
    resource: receive_transactions
    alias: receive_transactions
    crud: 'create, read, update'

---
