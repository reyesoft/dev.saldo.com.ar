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
    name: marked_as_sent
    crud: 'read, update'
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
  -
    name: canceled_at
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
    crud: 'create, read, update'
  -
    resource: direct_transfers1
    alias: direct_transfers1
    crud: 'create, read, update'
  -
    resource: direct_transfers2
    alias: direct_transfers2
    crud: 'create, read, update'
  -
    resource: future_invoices
    alias: future_invoices
    crud: 'create, read, update'

---
