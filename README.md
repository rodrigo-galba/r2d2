# r2d2

CLI app to interact with cloud services

## Setup

Use **Cobra Generator**
```
go install github.com/spf13/cobra/cobra@latest
go mod init github.com/rodrigo-galba/r2d2
cobra init
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