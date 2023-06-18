# goit-node-js-CLI-app

## Command definitions:

- Get and display the entire list of contacts in the form of a table
  node index.js --action="list"
  ![List screenshot](https://monosnap.com/file/YHZ4eTzvGl1pNfWwQ5U3Wm0oY7BuOQ)

- Get a contact by id and output the contact object to the console or null, if there is no contact with such an id
  node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
  ![List screenshot](https://monosnap.com/file/Q9BaPuy5ZB9M42XP6mnKeBMieZDRln)

- Add a contact and display the object of the newly created contact in the console
  node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
  ![List screenshot](https://monosnap.com/file/pS1QZZ9qOgQkFYkxSazbVRlsF1ge09)

- Delete the contact and output to the console the object of the deleted contact or null, if the contact with such an id does not exist
  node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
  ![List screenshot](https://monosnap.com/file/Uh1fgrVZFjBLWzlVmNy79RZYdi8b6Y)
