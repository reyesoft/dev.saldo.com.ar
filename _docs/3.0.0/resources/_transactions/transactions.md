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
    crud: read
    sortable: 'true'
  -
    name: state
    crud: read
    sortable: 'true'
  -
    name: mid
    crud: read
    sortable: 'true'
  -
    name: amount1
    crud: read
    sortable: 'true'
  -
    name: account_address1
    crud: read
    sortable: 'true'
  -
    name: instructions_url
    crud: read
    sortable: 'true'
  -
    name: cuenta1
    crud: read
    sortable: 'true'
  -
    name: amount2
    crud: read
    sortable: 'true'
  -
    name: account_address2
    crud: read
    sortable: 'true'
  -
    name: cuenta2
    crud: read
    sortable: 'true'
  -
    name: public_observation
    crud: read
    sortable: 'true'
relationships:
  -
    resource: system1
    alias: system1
    crud: read
  -
    resource: system2
    alias: system2
    crud: read
  -
    resource: invoice
    alias: invoice
    crud: read
  -
    resource: states
    alias: states
    crud: read
  -
    resource: files
    alias: files
    crud: 'read, update'

---
