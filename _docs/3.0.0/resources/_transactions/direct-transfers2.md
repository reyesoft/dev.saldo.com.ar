---
resource: direct_transfers2
permalink: /docs/3.0.0/resources/direct_transfers2/
version: 3.0.0
singular: resource
section: Transactions
partOf: t
attributes:
  -
    name: received
    crud: 'read, update'
    sortable: 'true'
  -
    name: amount
    crud: read
    sortable: 'true'
  -
    name: payment_identification
    crud: read
    sortable: 'true'
  -
    name: amount_without_fee1
    crud: read
    sortable: 'true'
  -
    name: amount_without_fee2
    crud: read
    sortable: 'true'
  -
    name: sent
    crud: read
    sortable: 'true'
relationships: {  }

---
