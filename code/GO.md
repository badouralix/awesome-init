# Go

## Init Project

We will use go modules. More info on <https://go.dev/ref/mod>.

```bash
go mod init github.com/$USER/$PROJECT
```

## Boilerplate

Below is the content of `main.go`.

```go
package main

func main() {

}
```

## Dependencies

The following command installs new dependencies to the project.

```bash
# For new dependencies
go get ...

# If the dependencies are already in the source code
go mod tidy
```

See also <https://golangbyexample.com/add-dependency-module-golang>.

## Execution

The following command runs the local code.

```bash
go run main.go
```
