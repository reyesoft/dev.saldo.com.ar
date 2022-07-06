---
resource: states
permalink: /docs/3.0.0/resources/states/
version: 3.0.0
singular: resource
section: Transactions
partOf: t
attributes:
  -
    name: transaction_id
    crud: 'create, read'
    sortable: 'true'
  -
    name: state
    crud: read
    sortable: 'true'
  -
    name: author_id
    crud: 'create, read'
    sortable: 'true'
  -
    name: author_name
    crud: read
    sortable: 'true'
  -
    name: updated_at
    crud: read
    sortable: 'true'
  -
    name: public_text
    crud: 'create, read'
    sortable: 'true'
  -
    name: state_action_id
    crud: read
    sortable: 'true'
relationships:
  -
    resource: state_actions
    alias: state_actions
    crud: 'create, read, update'

---
