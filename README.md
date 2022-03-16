# Vyshnavi Tadipaneni
# beam-go

## commands i have used for this project:
### check your GO version
        go version
### The go mod init command creates a go.mod file to track your code's dependencies.
        go mod init github.com/vyshnavi1996/beam-go
### Get the SDK and the examples.
        go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
### I have installed wordcount.
        go install github.com/apache/beam/sdks/v2/go/examples/wordcount
### executing a wordcount.go with sample input file.
        go run wordcount.go --input sample.txt --output vyshnavi.txt
