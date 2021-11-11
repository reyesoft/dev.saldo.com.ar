---
resource: transactions_states_public
permalink: /docs/3.0.0/resources/transactions_states_public/
version: 3.0.0
singular: resource
section: Transactions
attributes:
  -
    name: email
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
    name: amount2
    crud: read
    sortable: 'true'
  -
    name: currency1
    crud: read
    sortable: 'true'
  -
    name: currency2
    crud: read
    sortable: 'true'
  -
    name: system1
    crud: read
    sortable: 'true'
  -
    name: system2
    crud: read
    sortable: 'true'
  -
    name: token
    crud: read
    sortable: 'true'
relationships:
  -
    resource: states
    alias: states
    crud: 'create, read, update'

---
