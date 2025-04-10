# protocs
This repository contains **Protocol Buffers (protobuf)** API definitions for project services [AuthService].

# Repository structure

/protoFiles  
├── sso/                   
    ├── sso.pb.go
    ├──sso_grpc.pb.go
    └── sso.proto
 

## There 2 options
- register user (will add user data to database)
- login user (check user data and return JWT token)
