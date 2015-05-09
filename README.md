## Example REST API

## Getting Started

1. Install Go: `brew install go`
2. Install Fresh for live-reload: `go get github.com/pilu/fresh`
3. Install Foreman: `brew install foreman`
4. Create database: `createdb segment-go-test`
5. Run: `fresh`

## Deployment and Dependencies

The recommended way to manage Go package dependencies on Heroku is with [Godep](http://github.com/kr/godep), which helps build applications reproducibly.

1. Install Godep: go get github.com/kr/godep
2. Save dependencies: `godep save`
