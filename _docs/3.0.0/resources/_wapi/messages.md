---
resource: messages
permalink: /docs/3.0.0/resources/messages/
version: 3.0.0
singular: resource
section: Wapi
attributes:
  -
    name: from
    crud: read
    filter: NumberFilter
    sortable: 'true'
  -
    name: to
    crud: read
    sortable: 'true'
  -
    name: message
    crud: read
    sortable: 'true'
  -
    name: sent
    crud: 'read, update'
    filter: BooleanFilter
    sortable: 'true'
  -
    name: created_at
    crud: read
    filter: DateFilter
    sortable: 'true'
relationships: {  }

---
