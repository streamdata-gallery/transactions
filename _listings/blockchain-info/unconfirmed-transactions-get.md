---
swagger: "2.0"
info:
  title: Blockchain Info Unconfirmed Transactions
  description: Returns unconfirmed transactions.
  version: 1.0.0
host: blockchain.info
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /unconfirmed-transactions:
    get:
      summary: Unconfirmed Transactions
      description: Returns unconfirmed transactions
      operationId: getUnconfirmedTransactions
      responses:
        200:
          description: OK
      tags:
      - blockchain
      - transactions
definitions: []
x-collection-name: Blockchain Info
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---