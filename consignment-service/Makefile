echoit:
	@echo "${PATH}"
	@echo "$(GOPATH)/src/github.com/IoannisMit/shipper/consignment-service"

build:
	protoc -I. --go_out=plugins=grpc:. \
		"proto\consignment\consignment.proto"

buildspecific:
	protoc -I. --go_out=plugins=grpc:"$(GOPATH)\src\github.com\IoannisMit\shippy-service-consignment\consignment-service" \
		"proto/consignment/consignment.proto"