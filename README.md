# docker-volumes

## Build
docker build -t test-alona .

## Run
docker run --rm -v `/full-path`/src:/tmp/finastra/src -v `/full-path`/dest:/tmp/finastra/dest test-alona
