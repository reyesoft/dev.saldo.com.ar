---
resource: invoices
permalink: /docs/3.0.0/resources/invoices/
version: 3.0.0
singular: resource
section: Transactions
partOf: t
attributes:
  -
    name: amount
    crud: read
    sortable: 'true'
  -
    name: status
    crud: read
    sortable: 'true'
  -
    name: status_message
    crud: read
    sortable: 'true'
  -
    name: invoice_url
    crud: read
    sortable: 'true'
relationships:
  -
    resource: transaction
    alias: transaction
    crud: 'create, read'
  -
    resource: user_fiscal_data
    alias: user_fiscal_data
    crud: 'create, read'

---
