# convox/proxy

Simple TCP proxy wrapper to implement proxy protocol when necessary

## Usage

#### Standard TCP proxy

    $ proxy 5000 encrypted.google.com:443 tcp

#### PROXY protocol

    $ proxy 7000 mybackend.local:5000 proxy