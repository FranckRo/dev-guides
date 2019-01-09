###NPM Commands

- npm login (or npm adduser) \
_Connect to the default repository_ 
- npm login --registry=https://yourrepository.com \
_Connect to a specific repository. This can be useful if you manage multiples registries (public, private, etc.) and if you want to publish a specific module on a private repository._
- npm publish \
_Publish a component. The package.json of your module can contains a "publishConfig" attribute to specify a specific registry (overwrite the default registry of your .npmrc)_  

