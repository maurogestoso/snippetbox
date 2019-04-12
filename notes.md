### Enable modules for the project

```
go mod init maurogestoso.github.io/snippetbox
```

This command creates `go.mod`, which will keep track of the 3rd party packages required by our project.

```
module maurogestoso.github.io/snippetbox

go 1.12
```

## Web Application Basics

The essentials:

- A handler, which is equivalent to a controller in MVC. It will execute the app logic and write the HTTP response
- A router (`servemux` in Go), which maps URL patterns to handlers.
- A web server.
