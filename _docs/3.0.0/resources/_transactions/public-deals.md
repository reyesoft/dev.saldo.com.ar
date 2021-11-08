---
resource: public_deals
permalink: /docs/3.0.0/resources/public_deals/
version: 3.0.0
singular: resource
section: Transactions
attributes:
  -
    name: id
    crud: 'create, read, update'
  -
    name: group_id
    crud: 'create, read, update'
  -
    name: currency
    crud: 'create, read, update'
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
