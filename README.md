#Project overview.
🚀 Main Features Implemented
✅ Authentication
Google Sign-in with tokens (accessToken, refreshToken, authToken)

OTP-based verification for email and mobile

Session handling via JWT

First login logic with welcome notifications

✅ User Management
User creation & CRUD (crudRoutes, crud_userUpdateRoute, crudDeleteUserClassRoute)




#Steps to set up and run the project locally.
take pull of my code from https://github.com/vidya7s/test898.git      
then Run command npm run dev

#Details of the deployed API (base URL).
https://898testvidya-n296cp92i-vidya7s-projects.vercel.app/
this is not working

#Provide a Postman collection link.
https://planetary-escape-413361.postman.co/workspace/New-Team-Workspace~3c4c5020-530b-45f7-b38d-31e5b7d405e6/collection/32607225-712c8209-744b-4277-964f-44b2585af94e?action=share&creator=32607225&active-environment=32607225-269d7626-e95f-4104-92e2-89471a8bbcd1

#Include all API endpoints with example requests and responses. Also the collection to read or list all tasks example should have a sample authorization header to check.
signup:http://localhost:4000/api/AS/signup
login:http://localhost:4000/api/AS/login
edit:http://localhost:4000/api/AS/edit/users/:emailid
Delete:http://localhost:4000/api/AS/users/:emailid
get: http://localhost:4000/api/AS/Account/user-and-class-details-by-email/test@example.com

#Deployment details.
