---
resource: transaction_temporal_values
permalink: /docs/3.0.0/resources/transaction_temporal_values/
version: 3.0.0
singular: resource
section: Transactions
attributes:
  -
    name: state
    crud: read
    sortable: 'true'
  -
    name: url
    crud: read
    sortable: 'true'
relationships:
  -
    resource: channels_tokens
    alias: channels_tokens
    crud: 'create, read, update'

---
