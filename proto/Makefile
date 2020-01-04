echoit:
	@echo "${PATH}"
	@echo "$(GOPATH)/src/github.com/IoannisMit/shipper/consignment-service"

build:
	protoc -I. --go_out=plugins=grpc:. \
		"consignment\consignment.proto"

buildspecific:
	protoc -I. --go_out=plugins=grpc:"$(GOPATH)\src\github.com\IoannisMit\shippy\consignment-service" \
		"consignment/consignment.proto"