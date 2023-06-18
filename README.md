# goit-node-js-CLI-app

## Command definitions:

- Get and display the entire list of contacts in the form of a table
  node index.js --action="list"
  ![List screenshot](https://d3dehtdmp2rwcw.cloudfront.net/ms_586519/NqxtEUSiPHwVXzfROoa2jdquQCFFQl/README.md%2B-%2BCLI-app%2B-%2BVisual%2BStudio%2BCode%2B2023-06-1.png?Expires=1687129200&Signature=SMoMTflAgNkO3hnpD2Vvf81OJyLGvOcrq~chQtFAC7lh4xRTpbRQ8UKR65XxCOKO9ItGI~Ne~fvBOvLnHLBvkVchcNTN29fQyYZKGwMagAcWnyz1p9o6YFArO2u~gSVtpWrS7zZrG8ed79MpoPpY~MZM3-d1OchL1QaOEezyGG4JdRW~vnn6WTxq1Q5fXjj39qatNZmMK0WjkKx99WOrvHhBI4zGcK7YozIk4drHuvS0cclVm2hKR3Tx~ves0-6HdTLx0D7VHms9EKHwy4nQJCQ5uGXwgYr9~l6yXvZ6YevUSOOz4rVBi1Qnxush8EJB311H71p-tFWHbLOQnpAvrw__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

- Get a contact by id and output the contact object to the console or null, if there is no contact with such an id
  node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
  ![List screenshot](https://monosnap.com/file/Q9BaPuy5ZB9M42XP6mnKeBMieZDRln)

- Add a contact and display the object of the newly created contact in the console
  node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
  ![List screenshot](https://monosnap.com/file/pS1QZZ9qOgQkFYkxSazbVRlsF1ge09)

- Delete the contact and output to the console the object of the deleted contact or null, if the contact with such an id does not exist
  node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
  ![List screenshot](https://monosnap.com/file/Uh1fgrVZFjBLWzlVmNy79RZYdi8b6Y)
