# How to upgrade Golang version

1. `go mod edit -go=1.17`
1. `go mod vendor && go mod tidy`
1. Change Drone image in `.drone/drone.jsonnet`
1. Export $DRONE_SERVER and $DRONE_TOKEN environment variables (you can get them logging in to [https://drone.acme.net](https://drone.acme.net))
1. `make .drone/drone.yml`
