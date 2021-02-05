# PC builder app User Story to plan our application

| USER STORY | FRONTEND | BACKEND |
| --- | :---: |  :---: |
| User can see a list of PC builds |Make a get request for PC data and render it on the screen  |PC model with an index route  |
| User can add a PC build | Form to add that PC with selected hardware on submission which makes a post request| PC create route that adds a PC build to the database |
| User can update a PC build | Each PC build displayed should have an edit button that takes you to a form that makes the put request | PC update route that a PC by ID |
| User can remove a PC build | Each PC build displayed has a delete button when clicked which then sends a delete request |  A delete route that deletes a PC build by ID|