# DatingApp-Azure
Dating App with using Azure

(Angular 9 /.Net WebAPI Core (v 3.0) / Entity Framework core (v 3.0) / SQL Server) Dating App

- Role and Identity Management

- Using Entity Framework Core, persist data.

- Created a generic Repository using the Repository Pattern to offer another layer of abstraction to the Entity Framework.

- Show webapi problems on the client app using common error handling in Angular and.net core. Http Interceptors were used.

- AutoMapper was used in the heart of the webapi.

- Angular application includes 3rd party components such as Alertify.js as a service wrapper.

- Authentication using JWT Authentication Tokens for Webapi security.

- Lazy loading of relevant navigation properties in entities has been implemented, allowing Entity Framework core to load navigation properties only when they are required.

- Data filtering, sorting, and paging

- Integration with a cloud platform via drag-and-drop photo upload (cloudinary)

- Private messaging Chat system

- User can like profiles of other users( of opposite sex ) and can recieve likes from other users as well. Implemented Many-To-Many relationships.

- Global error Handling in the API and the SPA.

- ngx-loader to show loader on each http request and hide loader on http response.

- Implemeted Routing. Secured routes with CanActivate and CanDeActivate guards.

- Resolvers to pass data in route.

- Used Angular Reactive forms.

- Deployed to Azure

- HTTPS certificate applied
