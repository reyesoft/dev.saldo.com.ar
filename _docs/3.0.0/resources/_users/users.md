---
resource: users
permalink: /docs/3.0.0/resources/users/
version: 3.0.0
singular: resource
section: Users
attributes:
  -
    name: alias
    crud: 'create, read, update'
  -
    name: email
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: name
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: pass
    crud: 'create, update'
    sortable: 'true'
relationships:
  -
    resource: transactions
    alias: transactions
    crud: 'create, read, update'

---
