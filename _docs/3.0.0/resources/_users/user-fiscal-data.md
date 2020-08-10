---
resource: user_fiscal_data
permalink: /docs/3.0.0/resources/user_fiscal_data/
version: 3.0.0
singular: resource
section: Users
attributes:
  -
    name: cuit
    crud: 'create, read, update'
  -
    name: name
    crud: 'create, read, update'
  -
    name: responsibility
    crud: 'create, read, update'
  -
    name: address
    crud: 'create, read, update'
  -
    name: city
    crud: 'create, read, update'
  -
    name: province
    crud: 'create, read, update'
relationships:
  -
    resource: user
    alias: user
    crud: 'create, read, update'

---
