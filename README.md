# Angular-Services
Activity 23: Research Angular Services
Angular services

Angular services provide a way for you to separate Angular app data and functions that can be used by multiple components in your app. To be used by multiple components, a service must be made injectable. Services that are injectable and used by a component become dependencies of that component. The component depends on those services and can't function without them.

In Angular, services are a foundational concept that allows the sharing of data, logic, and functionality across multiple components or modules within an application. Services are typically used for tasks such as handling data retrieval, business logic, state management, or interacting with external APIs.

Key Features of Angular Services:

Singleton Design Pattern:
By default, Angular services are singletons, meaning that one service instance is shared across the application when provided in the root injector. This makes them efficient for sharing data and logic.

Dependency Injection:
Angular's dependency injection (DI) system makes it easy to inject services into components, other services, or directives where needed.

Separation of Concerns:
Services promote a clean separation between the business logic and the presentation layer (components). This helps in keeping components lean and focused on the view.

Reusability:
The logic in services can be reused across multiple application parts, reducing redundancy.
