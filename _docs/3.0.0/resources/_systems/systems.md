---
resource: systems
permalink: /docs/3.0.0/resources/systems/
version: 3.0.0
singular: resource
section: Systems
attributes:
  -
    name: amount
    crud: 'create, read, update'
  -
    name: currency
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: can_send
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: can_receive
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_required_send
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_required_receive
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: id_agreement
    crud: 'create, read, update'
  -
    name: minimum_amount_send
    crud: 'create, read, update'
  -
    name: minimum_amount_receive
    crud: 'create, read, update'
relationships:
  -
    resource: rates
    alias: rates
    crud: 'create, read, update'

---
