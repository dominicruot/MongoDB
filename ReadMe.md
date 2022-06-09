# MongoDB

## Notes:

MongoDB represents a radical and much needed departure from relational database technology

### What is NoSQL?

- Doesn't use SQL Language
- NoSQL db doesn't adhere to relational model.

![Relatopnal To MongoDB](https://beginnersbook.com/wp-content/uploads/2017/09/RDBMS_MongoDB_Mapping.jpg "Optional title")

### Using the MongoDB Shell
- Performing Simple Queries
- Database and Collection Operations
- Creating, Updating, or Deleting Documents
- Creating and Running Shell Scripts
- 
### Why use MongoDB Shell
The answer lies in the very nature of Compass; it's graphical in nature, which means you are
out of luck when a customer in another city (or even another country!) calls you late on a
Friday to tell you the database is down.
Although Compass can connect remotely, its requirements are much more demanding, and
you would most likely need the support of the customer IT department to successfully
connect. The mongo shell, on the other hand, is text based and only requires a simple,
relatively common SSH connection to a server on the customer site.
Another massive advantage of the mongo shell over Compass is that the shell can run scripts.
Getting back to the late Friday Emergency scenario, imagine being able to upload and run a
rescue script over an SSH connection, rather than trying to perform manual surgery on the
customer's database using Compass.
