# API

## Why?

Because we have multiple components (dashboard and mobile application), we needed one central place where all requests and data manupilation is getting handled.

## How?

The API is made in .NET 8 and is based on Clean architecture and Domain Driven Design.

### Clean architecture

Clean Architecture is chosen for its emphasis on maintainability, flexibility, and testability by organizing code with a clear separation of concerns. It isolates business logic from external frameworks, making the codebase more adaptable, scalable, and easier to maintain over the long term.

### Domain Driven Design

Domain-Driven Design (DDD) is chosen for its emphasis on aligning software development with business goals. It promotes a shared language between developers and stakeholders, focuses on core business logic, models complex domains effectively, and provides strategic design patterns for adaptability. DDD fosters collaboration, ensuring that the software accurately reflects the business domain and supports an evolutionary development process.

## Result

- An api that can create users based on the Auth0 api.
- Create innovations.
- Create Feedback on innovations.

![PSV Innovations API](/img/api/api-1.png)

## Conclusion

With this api we have a 1 point entry to manipulate data. The api also works together with Auth0 so it can create and login users.

The next step is to connect the dashboard and the application with this api, so they get live data.
