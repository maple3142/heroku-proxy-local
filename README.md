# Heroku proxy local

> Use Heroku to expose your local server to the Internet.

## Usage

1. [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
2. Download modified `wstunnel` [here](https://github.com/maple3142/wstunnel/releases)
3. Extract `wstunnel` binary from tarball
4. `./wstunnel cli -tunnel ws://$YOUR_APP_NAME.herokuapp.com -server http://localhost:$PORT`

	Example: `./wstunnel cli -tunnel ws://test.herokuapp.com -server http://localhost:8000`

5. Access `https://$YOUR_APP_NAME.herokuapp.com`

## About the binary `wstunnel`

It is built from my fork of `wstunnel` [here](https://github.com/maple3142/wstunnel).
