# portsnap-build

## First Time
sh -e setup.sh

cp world.tar in (magus tarball?)

sh -e keygen.sh

edit build.conf

sh -e loop.sh

## Client configuration changes

You will need to include the key from keygen in portsnap.conf for the client.  You will also need to create SRV records for the domain you include in that file in DNS for the _http.tcp 
