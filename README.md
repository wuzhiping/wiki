# wiki
https://wiki.js.org/

docker run --rm -it -p 3000:3000 \
             -v $PWD/db/:/wiki/db/ \
             -v $PWD/data/:/wiki/data/ \
             -v $PWD/config.sample.yml:/wiki/config.yml \
             ghcr.io/requarks/wiki:2
