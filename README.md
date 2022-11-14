# asynchronous-java
## Use Case
#### Consider a user apply for a product such as a credit card or debit card from front-end UI.
#### Now once at the backend, we receive user requests, we perform n number of use cases such as validation, transformation, persist to DB and sending acknowledgment email, etc.
#### Now all of these processes don’t have to be synchronous. For example, we can send emails to customers irrespective of saving them to the database.
So we can execute this piece of logic asynchronously.
