---
resource: transactions
permalink: /docs/3.0.0/resources/transactions/
version: 3.0.0
singular: resource
section: Transactions
partOf: t
attributes:
  -
    name: user
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: state
    crud: read
    sortable: 'true'
  -
    name: amount1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address1
    crud: 'create, read, update'
  -
    name: cuenta1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: amount2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address2
    crud: 'create, read, update'
  -
    name: cuenta2
    crud: 'create, read, update'
    sortable: 'true'
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
  -
    resource: invoice
    alias: invoice
    crud: 'create, read, update'

---
