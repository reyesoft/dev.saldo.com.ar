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
    crud: 'create, read'
    sortable: 'true'
  -
    name: observations
    crud: read
    sortable: 'true'
  -
    name: validation_type_id
    crud: 'create, read'
    filter: StringFilter
    sortable: 'true'
  -
    name: created_at
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: validable_type
    crud: create
    sortable: 'true'
  -
    name: validable_id
    crud: create
    sortable: 'true'
relationships:
  -
    resource: validation_type
    alias: validation_type
    crud: read
  -
    resource: files
    alias: files
    crud: 'create, read'

---
