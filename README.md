# Our application is a simple topic manager


Its functionality is as follows:
1. allow users to register with a username and password (for unauthorized users)
2. allow users to log in (for unauthorized users)
3. allow users to terminate the session (for authorized users)
4. allow users to create topics (for authorized users)
5. display a list of all topics on the main page (for all users)
6. display the topic on its own page (for all users)

please, run by command - 
go run main.go routes.go middleware.auth.go models.user.go models.article.go handlers.article.go handlers.user.go
