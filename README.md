# stac-proxy
A proxy to local/online STAC file

## Usage
Two environnement variable should be set :

* INPUT_STAC_URL is the local path or url to the STAC root endpoint to proxify
* PUBLIC_ENDPOINT is the new endpoint to access the proxified STAC root endpoint

Example :

    INPUT_STAC_URL=https://raw.githubusercontent.com/pdssp/pdssp-stac-repo/test/versions/v0.1/ias/catalog.json \
    PUBLIC_ENDPOINT=http://localhost:4112 \
    docker compose up
