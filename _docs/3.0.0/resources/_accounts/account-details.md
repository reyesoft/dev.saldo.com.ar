---
resource: account_details
permalink: /docs/3.0.0/resources/account_details/
version: 3.0.0
singular: resource
section: Accounts
partOf: u
attributes:
  -
    name: cuit
    crud: 'create, read, update'
  -
    name: holder
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: number
    crud: 'create, read, update'
    sortable: 'true'
relationships:
  -
    resource: account
    alias: account
    crud: 'create, read, update'

---