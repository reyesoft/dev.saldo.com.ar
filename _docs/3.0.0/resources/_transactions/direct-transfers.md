---
resource: direct_transfers
permalink: /docs/3.0.0/resources/direct_transfers/
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
relationships:
  -
    resource: account
    alias: account
    crud: read

---
