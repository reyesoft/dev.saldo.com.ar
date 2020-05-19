---
resource: currencies
permalink: /docs/3.0.0/resources/currencies/
version: 3.0.0
singular: resource
section: Systems
attributes:
  -
    name: key
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: usd_price
    crud: 'create, read, update'
relationships:
  -
    resource: best_rates
    alias: best_rates
    crud: 'create, read, update'

---
