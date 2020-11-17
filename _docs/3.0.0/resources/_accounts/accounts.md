---
resource: accounts
permalink: /docs/3.0.0/resources/accounts/
version: 3.0.0
singular: resource
section: Accounts
partOf: u
attributes:
  -
    name: email
    crud: 'create, read, update'
    sortable: 'true'
relationships:
  -
    resource: system
    alias: system
    crud: 'create, read, update'
  -
    resource: account_details
    alias: account_details
    crud: 'create, read, update'

---
