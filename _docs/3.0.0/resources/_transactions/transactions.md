---
resource: transactions
permalink: /docs/3.0.0/resources/transactions/
version: 3.0.0
singular: resource
section: Transactions
attributes:
  -
    name: name
    crud: create
    sortable: 'true'
    required: true
  -
    name: email
    crud: create
    sortable: 'true'
    required: true
  -
    name: phone_number
    crud: create
    sortable: 'true'
    required: true
  -
    name: user
    crud: 'create, read, update'
  -
    name: referrer_id
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: sistema1
    crud: 'create, read, update'
  -
    name: system1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: amount1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address1
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: cuenta1
    crud: 'create, read, update'
  -
    name: sistema2
    crud: 'create, read, update'
  -
    name: system2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: amount2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: account_address2
    crud: 'create, read, update'
    sortable: 'true'
  -
    name: cuenta2
    crud: 'create, read, update'
  -
    name: public_observation
    crud: 'create, read, update'
    sortable: 'true'
relationships: {  }

---
