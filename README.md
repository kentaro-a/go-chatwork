# go-chatwork
Simple way to send messages with Chatwork API in Go


# Installation
It's easy to install with dep.
```
$ dep ensure -add github.com/kentaro-a/go-chatwork
```


# Usage
Import package.
```
import (
	"github.com/kentaro-a/go-chatwork"
)
```



```
cw := chatwork.Api{ApiToken: "your apitoken"}
_, err := cw.SendMessageByName("room name you want to send to", "message")
if err != nil {
	// Handling here...
}
```
