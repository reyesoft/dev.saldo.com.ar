---
resource: user_validations
permalink: /docs/3.0.0/resources/user_validations/
version: 3.0.0
singular: resource
section: Users
partOf: u
attributes:
  -
    name: status
    crud: 'create, read, update'
  -
    name: observations
    crud: 'create, read, update'
  -
    name: validation_id
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: created_at
    crud: 'create, read, update'
    sortable: 'true'
relationships:
  -
    resource: user
    alias: user
    crud: 'create, read, update'
  -
    resource: validation
    alias: validation
    crud: 'create, read, update'

---
