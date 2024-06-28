gen_codeRunner:
	protoc -I proto proto/code-runner.proto --go_out=./gen/code-runner/ --go_opt=paths=source_relative --go-grpc_out=./gen/code-runner/ --go-grpc_opt=paths=source_relative

gen_auth:
	protoc -I proto proto/auth.proto --go_out=./gen/auth/ --go_opt=paths=source_relative --go-grpc_out=./gen/auth/ --go-grpc_opt=paths=source_relative