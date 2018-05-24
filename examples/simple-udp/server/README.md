# Getting Started

## Prerequisites

1. Install golang from https://golang.org/doc/install.
2. Install kubectl and gcloud by following the instruction https://github.com/GoogleCloudPlatform/agones.

## Build Server
```bash
>> go get agones.dev/agones/pkg/sdk
>> go build -o bin/server main.go
```

## Deploy Server
```bash
>> kubectl apply -f gameserver.yaml
```
