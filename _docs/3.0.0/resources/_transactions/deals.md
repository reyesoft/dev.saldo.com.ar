---
resource: deals
permalink: /docs/3.0.0/resources/deals/
version: 3.0.0
singular: resource
section: Transactions
attributes:
  -
    name: transaction_id
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: group_id
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: rest_to_pay
    crud: 'create, read, update'
  -
    name: gain_percent
    crud: 'create, read, update'
relationships:
  -
    resource: system
    alias: system
    crud: 'create, read, update'

---
