---
resource: accounts
permalink: /docs/3.0.0/resources/accounts/
version: 3.0.0
singular: resource
section: Accounts
partOf: u
attributes:
  -
    name: address
    crud: 'create, read'
    filter: StringFilter
    sortable: 'true'
  -
    name: alias
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: status
    crud: 'read, update'
    filter: EnumFilter
    sortable: 'true'
  -
    name: deleted_at
    crud: 'create, read, update'
    filter: DeletedFilter
    sortable: 'true'
relationships:
  -
    resource: system
    alias: system
    crud: 'create, read'
  -
    resource: account_detail
    alias: account_detail
    crud: 'create, read, update'

---
