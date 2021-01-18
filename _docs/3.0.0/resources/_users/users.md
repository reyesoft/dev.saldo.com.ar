---
resource: users
permalink: /docs/3.0.0/resources/users/
version: 3.0.0
singular: resource
section: Users
attributes:
  -
    name: alias
    crud: read
    sortable: 'true'
  -
    name: email
    crud: 'create, read'
    sortable: 'true'
  -
    name: name
    crud: 'create, read'
    sortable: 'true'
  -
    name: level
    crud: read
    sortable: 'true'
  -
    name: referrer_balance
    crud: read
    sortable: 'true'
relationships:
  -
    resource: transactions
    alias: transactions
    crud: 'create, read, update'

---
