when you want to open backend,running in container, you should go to http://localhost:8080/api/api/blogs (I didn't find solution to fix it)
## docker-compose -f docker-compose.dev.yml up
## docker-compose up
I couldn't solve the problem when running app in production mode with command docker-compose up:
when I am on one of the tabs(blogs, create new, about, users) and reload the page, it gives me a 404 error.