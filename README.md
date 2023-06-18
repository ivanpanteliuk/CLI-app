# goit-node-js-CLI-app

## Command definitions:

- Get and display the entire list of contacts in the form of a table
  node index.js --action="list"
  ![List screenshot](https://d3dehtdmp2rwcw.cloudfront.net/ms_586519/NqxtEUSiPHwVXzfROoa2jdquQCFFQl/README.md%2B-%2BCLI-app%2B-%2BVisual%2BStudio%2BCode%2B2023-06-1.png?Expires=1687129200&Signature=SMoMTflAgNkO3hnpD2Vvf81OJyLGvOcrq~chQtFAC7lh4xRTpbRQ8UKR65XxCOKO9ItGI~Ne~fvBOvLnHLBvkVchcNTN29fQyYZKGwMagAcWnyz1p9o6YFArO2u~gSVtpWrS7zZrG8ed79MpoPpY~MZM3-d1OchL1QaOEezyGG4JdRW~vnn6WTxq1Q5fXjj39qatNZmMK0WjkKx99WOrvHhBI4zGcK7YozIk4drHuvS0cclVm2hKR3Tx~ves0-6HdTLx0D7VHms9EKHwy4nQJCQ5uGXwgYr9~l6yXvZ6YevUSOOz4rVBi1Qnxush8EJB311H71p-tFWHbLOQnpAvrw__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

- Get a contact by id and output the contact object to the console or null, if there is no contact with such an id
  node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
  ![List screenshot](https://d3dehtdmp2rwcw.cloudfront.net/ms_586519/9DvQzlFVjK9RXYeK2wY3nLfYvJPjGQ/README.md%2B-%2BCLI-app%2B-%2BVisual%2BStudio%2BCode%2B2023-06-1.png?Expires=1687129200&Signature=LBLtz~4OIGY~w8KNAopgo43AhkusnrX1z8OHlE8YPjdCwIJrBd46xzGa3trifOEfLPKiUu-ONqkvDSa7BCHbKt-F~rhkVoCSChWm-EXbwwY5qz1jdiMJKvzO8-tpnmXs~7sMGN0DffKzwEMjJr6-F8dffjVp3BxsIaF4hsOLJCrD~~aUpt41LFGEsS-SK5-4dlAZGe7CqKwdAhIVXD6MaJrXLw9HhqYEMp9rBkFefQ-G6TF6iGaMeO-uxQfRLwAF5-fXgZpb0PaWR0~qJxW1oRNSdaLVOj~hYHZgEpHZcM1U5sJb02azMhk0JUcblaS0d323wG9O1-TI82ba-~xpaQ__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

- Add a contact and display the object of the newly created contact in the console
  node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
  ![List screenshot](https://d3dehtdmp2rwcw.cloudfront.net/ms_586519/qNthRAjNXEOwHHtVirNikA5sxWrm7y/README.md%2B-%2BCLI-app%2B-%2BVisual%2BStudio%2BCode%2B2023-06-1.png?Expires=1687129200&Signature=t~zLHEw0w6rVkzqx7NcGRSVo6zdX-UK03Q-zg-0tvKw9LrVhUnnKG4449YSMqGU93p3xUo8pF68XRLymNQyzQ0yNzvuVJwsuRxWQxpj36nKPg~pnruUp57ArrNhcvXIeH7BqkEq5ncyl3VFFkGj4e9knJV0T5I9iJtbaIqziGgwFvLjMqNjLLsBN1YlNWF5xMEe6o5WxpfWYS~v6rI4OlM7SoUi5AJPph80lKWqwtXzzt0WRMIzfcrfr3BeD7s3bAZjBItrB4S9dhvgNkHV3vYvBgHhgbhnfVzw5FBqhCEA6F1IZ3WO762eVjXnP-ct9MVzj6fnW~fJfx1hr54cweQ__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)

- Delete the contact and output to the console the object of the deleted contact or null, if the contact with such an id does not exist
  node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
  ![List screenshot](https://d3dehtdmp2rwcw.cloudfront.net/ms_586519/1E9cRk8XpFVPgDDb5ovPvx7kORZHPp/README.md%2B-%2BCLI-app%2B-%2BVisual%2BStudio%2BCode%2B2023-06-1.png?Expires=1687129200&Signature=fBS4YCkgK5nsx0d-yx5Sbq~JViNVSwgKuD~1jiRrPSHkwyL03~S7Ps7zdam0LDyayuQbrciE~3Uv6kGne5MhyqwuzrJ2EGNxrO6H74K6p~vZ-KCrWeebqH2iswgCj6epnO57KKcfxQxRUXGyhqK5AkmBa~RTDZVIoULP2NKL5jpD-B2l2LdE9xY-d1drQIaowRRpd3ClRbD-SurvcEDUiIBKlawOOYmHmnlbakgapwliFrWJrcJxmBrlHPoSxAuiPiEaiH2tF7TZxhDrf-DHbow1QoFKD8hIEJ8umzNAZ8PUDVXNaGBU6d0pBe4FAfNq9iYNKlcNvPuhiIGa90SQRQ__&Key-Pair-Id=APKAJBCGYQYURKHBGCOA)
