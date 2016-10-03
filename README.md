# Render Noodels Windows Background Service [RNWBS] (Tested on Windows Only) 

#### Windows Background Service act as websocket client and it responsable for:
   - connect to websocket of server.
   - send current state of machine.
        - watch process and send what is running and what is not.
        - watch cpu and memory usage. 
   - receive commands and execute them.
   - connect to tray client ui and tell it connection status.

## Dependencies

### Go Packages

    $ go get github.com/kardianos/service 
    
    $ go get github.com/spf13/viper
    
    $ go get github.com/gorilla/websocket

    $ go get github.com/pebbe/zmq4
    // need gcc compiler run from mingw [ msys2 or cygwin ] 

## Packages
### #service Package
    program.go
    main.go

### #websocket Package

### #commands Package

### #proccess-watcher


-----
## Testing

t