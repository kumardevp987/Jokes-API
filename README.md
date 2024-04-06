# Jokes-API
## Documentation:

### GET METHOD

GET '/': Welcomes users to the Jokes API.

GET '/reset': Resets all jokes to the original data.

GET '/random': Retrieves a random joke from the list of jokes.

GET '/jokes/:id': Retrieves a specific joke based on the provided ID.

GET '/filter': Retrieves jokes filtered by type. It expects a query parameter 'type' to filter jokes.

POST '/jokes': Adds a new joke to the list. Expects 'text' and 'type' in the request body.

PUT '/jokes/:id': Updates an existing joke. Expects 'text' and 'type' in the request body.

PATCH '/jokes/:id': Partially updates an existing joke. Expects either 'text' or 'type' in the request body.

DELETE '/jokes/:id': Deletes a specific joke based on the provided ID.

DELETE '/all': Deletes all jokes. Expects a query parameter 'key' for authorization.
