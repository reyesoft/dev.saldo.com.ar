---
resource: systems
permalink: /docs/3.0.0/resources/systems/
version: 3.0.0
singular: resource
section: Systems
attributes:
  -
    name: name
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: amount
    crud: 'create, read, update'
  -
    name: currency
    crud: 'create, read, update'
    filter: EnumFilter
    sortable: 'true'
  -
    name: decimal_places
    crud: 'create, read, update'
  -
    name: can_send
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: can_receive
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: fee_send
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: fee_receive
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
  -
    name: maximum_amount_send
    crud: 'create, read, update'
  -
    name: maximum_amount_receive
    crud: 'create, read, update'
  -
    name: account_type
    crud: 'create, read, update'
  -
    name: group_id
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: market
    crud: 'create, read, update'
relationships:
  -
    resource: rates
    alias: rates
    crud: 'create, read, update'
  -
    resource: currency
    alias: currency
    crud: 'create, read, update'

---
