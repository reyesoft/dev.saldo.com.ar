---
resource: rate_stats
permalink: /docs/3.0.0/resources/rate_stats/
version: 3.0.0
singular: resource
section: Systems
attributes:
  -
    name: registered_at
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: systems
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: price
    crud: 'create, read, update'
    sortable: 'true'
relationships: {  }

---
