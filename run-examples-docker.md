### cip


####
    docker run --init --rm -v /workspaces/prism/examples:/examples -p 4010:4010 stoplight/prism:4 mock -h 0.0.0.0 "/examples/api-specification.yaml"


### veridas

####
    docker run --init --rm -v /workspaces/prism/examples:/examples -p 4010:4010 stoplight/prism:4 mock -h 0.0.0.0 "/examples/xpressid.yaml"

