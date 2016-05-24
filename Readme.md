# mup-frontend-server-BIG-requests

The mup tool for `Meteor` is from `mupx` onwards using the docker image [`meteorhacks/mup-frontend-server`](https://hub.docker.com/r/meteorhacks/mup-frontend-server/). This docker images uses `nginx` and has a limit on the
request size of 10M. We ran into this limit, so this is a small replacement
that increases the request size to 200M.
