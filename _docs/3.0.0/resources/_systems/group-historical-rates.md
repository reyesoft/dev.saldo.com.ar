---
resource: group_historical_rates
permalink: /docs/3.0.0/resources/group_historical_rates/
version: 3.0.0
singular: resource
section: Systems
attributes:
  -
    name: date
    crud: read
    filter: DateFilter
    sortable: 'true'
  -
    name: pair
    crud: read
    filter: StringFilter
    sortable: 'true'
  -
    name: ask_price
    crud: read
    sortable: 'true'
  -
    name: bid_price
    crud: read
    sortable: 'true'
relationships: {  }

---
