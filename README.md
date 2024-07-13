# AI Certs Assignment ( Devki Nandan)

Hello, my name is Devki Nandan. I completed the assignment using Node.js, React.js, and Tailwind CSS, performing all CRUD operations without using any databases, as instructed. I've included videos and links to the scripts demonstrating the functionality of both the frontend and backend.

Previously, I built a server capable of handling up to 2,000 requests in 1.5 minutes.

##  Backend:

1) I used Node.js to build a server and created all the CRUD APIs.
2) Since the frontend and backend were running on different domains, I used the CORS library.
3) We can use the cluster library to create instances for CPU cores, allowing us to scale the system vertically.
4) We can use HTTPS for both the frontend and backend to secure communication by generating SSL certificates.

## Frontend: 

1) I used the React framework to build the frontend.
2) I used Tailwind CSS for styling.
3) I built a basic UI to create, delete, and edit tasks.

## Codes links:
   ### Backend: https://replit.com/@dalveerdnsingh/AI-Certs
   ### Frontend: https://replit.com/@dalveerdnsingh/AI-CERT

   There is one fork in the backend script, which was done by me.
   
## Videos links:
  ### Frontend & Backend Scripts: https://www.loom.com/share/fadbc7bf47e844439f75dcba2c861999?sid=16ad095a-ef4f-42f2-9266-61bd14e20cde
  
  ### Frontend and Backend Working: https://www.loom.com/share/ec56bff8109345f6b828379b974e06bc?sid=ce5426cd-2740-4c78-8d0c-f3ab46fd6736

  ## Working Explanation:
   1)I started the backend server and frontend, demonstrating that initially, no tasks were available.
   2)  I proceeded by adding tasks and showcasing operations such as create, edit, and delete (GET, DELETE, PUT, POST).
   3) Using Postman, I demonstrated how to fetch a single record and tested the APIs for functionality.
   4) Finally, I stopped the server and showed that tasks were no longer accessible, highlighting the server's essential role in data retrieval.


# How to Run code: 
1) Create an account on Replit and fork both the frontend and backend reples.
2) Run both the frontend and backend repl to access the working application.
3) If you encounter errors due to different base URLs, copy the base URL provided (base Replit URLs could be different for you) and update it in the frontend JavaScript code where fetch operations are performed. Only update the base URL and not the endpoint mentioned below.

# API'S End-Points: 
   1) GET "/task" : To retrieve all tasks.
   2) GET "/task/:id" : To retrieve a specific task by ID.
   3) POST "/task" : To create a new task.
   4) PUT "/task/:id" : To update a specific task by ID.
   5) DELETE "/task/:id" : To delete a specific task by ID.


# Help:
  If you encounter any issues, please feel free to contact me.
