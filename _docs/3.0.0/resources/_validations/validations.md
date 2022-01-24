---
resource: validations
permalink: /docs/3.0.0/resources/validations/
version: 3.0.0
singular: resource
section: Validations
partOf: u
attributes:
  -
    name: status
    crud: 'create, read, update'
  -
    name: observations
    crud: 'create, read, update'
  -
    name: validation_type_id
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: created_at
    crud: 'create, read, update'
    sortable: 'true'
relationships:
  -
    resource: validation_type
    alias: validation_type
    crud: 'create, read, update'

---
