# r2d2

CLI app to interact with cloud services

## Setup

Use **Cobra Generator**
```
go install github.com/spf13/cobra/cobra@latest
go mod init github.com/rodrigo-galba/r2d2
cobra init --viper
go run main.go
go build
.\r2d2.exe
```

## Add a commands to a project

```
cobra add help
```

#### References

- https://github.com/spf13/cobra/blob/master/cobra/README.md
- https://github.com/spf13/viper

## Demystifying GOPATH

> `GOPATH` is nothing but the current appointed  workspace on your machine.  
It is an environment variable that tells the GO compiler where your sourcecode, binaries and packages are placed.  
It is similar to `Virtualenv` for Python.  
But at a given time, you can activate the environment for the project that you wish to work on and develop your project. Similarly, you can have any number of Go projects on your machine. While developing, set the GOPATH to one of your projects. The Go compiler now activates that project.

> It is a common practice to create a project under the home directory and set the GOPATH environment variable as follows:
```shell
mkdir /home/user/workspace
export GOPATH=/home/user/workspace
```
> Now, we install external packages like this:

```shell
go get -u -v github.com/gorilla/mux
```

> Go copies a project called mux from GitHub into the currently activated project workspace.
