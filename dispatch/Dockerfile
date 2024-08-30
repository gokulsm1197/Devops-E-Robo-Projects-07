# Use Go 1.19 as the base image
FROM golang:1.19

# Set the working directory inside the container
WORKDIR /go/src/app

# Copy all Go source files into the container
COPY *.go .

# Initialize the Go module and download dependencies
RUN go mod init dispatch && go mod tidy

# Build the Go application
RUN go build -o main .

# Set the command to run the compiled binary
CMD ["./main"]
