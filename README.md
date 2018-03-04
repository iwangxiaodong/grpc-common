# grpc-common


    go get github.com/iwangxiaodong/grpc-common

    cd C:\Users\xiaodong\go\src\github.com\iwangxiaodong\grpc-common\files\my\api
    
    protoc -I. --go_out=plugins=grpc:$HOME/go/src --plugin=protoc-gen-go=$HOME/go/bin/protoc-gen-go.exe my.proto
