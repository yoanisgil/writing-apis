# On writing API and shipping them to production

- Choose a Language and a Framework (specially one that doesn't get in your way)
- Understand as much as you can how your API is going to be used and it's scope.
- Have very clear API contracts.
- If possible your API contract/document should live as close as possible to your API code (Swagger/Open API, HAL, etc)
- Test your API (specially the contract)
- Protect your API (authentication/authorization)
- Deploy your API
- Monitoring
- Logging

# How would you teach someone to write an API? (someone that's never written an API ever never before)

Write the easiest/dumbest possible thing:

- Choose an API that helps solving a simple problem (ex: the Calculator API)
- Introduce the Framework (and explain why it was choosen)
- Document one endpoint
- Code/Test the endpoint
- Document/Code/Test more endpoints

Deploy the API:

- Deploy, YES ... but where?
- Depending on the selected Framework, explain what's required to deploy the application to a production environment
- Deploy the thing manually (without Docker)
- Let people see all of the problems that comes with it
- Go back to the appliation and Dockerize it
- Deploy the application on the simplest possible Stack (Digital Ocean ??)

# More Advanced stuff

- Micorservices 
- Autoscaling
- The Kitchen Sink!

