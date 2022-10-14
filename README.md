# Task 2

---
---

### create the following API endpoints:

```
# to list all posts
GET /posts

# to retrieve a certain post
GET /posts/{title}

# to create a new post
POST /posts

# to update a certain post
PUT /posts/{title}
```

Each endpoint should serve only one method, please read the note below and follow the instructions.

You can use any of the methods in utils.py, however you should implement the endpoint on your own.

You have to set up NinjaAPI object, add routers to controllers.py, and as a bonus for extra points, you should implement
the DELETE method.

'posts' directory is where you should save/update and create posts, each file is a markdown file where the filename is
the title of the post and the file content is the content of the post. Each file represents a single post. A sample of
two files (two blog posts) are there for your reference.

###### bonus:

```
# to delete a certain post
DELETE /posts/{title}
```

### Note

* you can utilize any third party library or package
* you should use the included utils.py