# Mirror for node-sass binaries
Node-sass binaries are hosted on github, and their links are redirected to AWS. If your local proxy/firewall prevents access to AWS, you can force node-sass to use this mirror by overriding one of node-sass parameters. 3 possibilities:

## Environment variable
`export SASS_BINARY_SITE=https://github.com/aversini/node-sass-binaries/raw/master/`

## .npmrc configuration file
`npm config set sass_binary_site https://github.com/aversini/node-sass-binaries/raw/master/`

## Process argument
`npm install node-sass --SASS_BINARY_SITE=https://github.com/aversini/node-sass-binaries/raw/master/`
