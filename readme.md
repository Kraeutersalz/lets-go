go get
go install

https://github.com/cosmtrek/air
go install github.com/cosmtrek/air@latest

Under build in the air.toml; you might want to change the cmd property. If the entry of your golang application is in a different directory, say server, you can change the property to something like this:

cmd = "go build -o ./tmp/main ./server/main.go"