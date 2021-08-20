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
    name: pass
    crud: create
    sortable: 'true'
  -
    name: password
    crud: create
    sortable: 'true'
  -
    name: phone_number
    crud: 'read, update'
    sortable: 'true'
  -
    name: level
    crud: read
    sortable: 'true'
  -
    name: referral_balance
    crud: read
    sortable: 'true'
relationships:
  -
    resource: transactions
    alias: transactions
    crud: 'create, read, update'

---
