## Dev Dependencies

- Golang 1.20+
- Kubebuilder v3

## Running Operator Locally

- make run

## Watch a namespace

- export WATCH_NAMESPACE="" # For all namespaces
- export WATCH_NAMESPACE="mynamespace" # For single namespace
- export DENY_LIST="kube-system,default" # watch all ns but kube-system, default

## Building Operator Docker Image

- make docker-build

## More

- make help
- Please see the Makefile.
