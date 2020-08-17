---
resource: transactions
permalink: /docs/3.0.0/resources/transactions/
version: 3.0.0
singular: resource
section: Transactions
partOf: u
attributes:
  -
    name: user
    crud: 'create, read, update'
  -
    name: amount1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: cuenta1
    crud: 'create, read, update'
  -
    name: amount2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: cuenta2
    crud: 'create, read, update'
  -
    name: public_observation
    crud: 'create, read, update'
    sortable: 'true'
relationships:
  -
    resource: system1
    alias: system1
    crud: 'create, read, update'
  -
    resource: system2
    alias: system2
    crud: 'create, read, update'

---
