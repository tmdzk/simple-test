# DevOps Test.

#### 1. Code and design a simple api following those endpoints, storage/database can be either a fs or db:

###### Insert a graduation date:
---

  **Request**: PUT /graduation-date/{username}

  **Body**: { "graduation-date": "YYYY-MM-DD" }

  **Response**: 204 No Content


###### Get a graduation date:
---
  **Request**: GET /graduation-date/{username}

  **Body**:

  **Response**: 200 ok


Response can either be:

{ "message": "Is graduated" } or  { "message": "Is not graduated" }



#### 2. Design how you would deploy your solution to a cloud provider (AWS, GCP, Azure, Scaleway..)


#### 3. Make a graph on how you would manage CI/CD for your solution.


Some hints:

- Think about efficiency     
- Test things before going into production     
- Build once run anywhere
