[Home](../README.md) 

###NPM commands

- <code> npm login (or npm adduser) </code>
_Connect to the default repository_ 
- <code> npm login --registry=https://yourrepository.com </code> 
_Connect to a specific repository. This can be useful if you manage multiples registries (public, private, etc.) and if you want to publish a specific module on a private repository._
- <code> npm publish </code>
_Publish a component. The package.json of your module can contains a "publishConfig" attribute to specify a specific registry (overwrite the default registry of your .npmrc)_  

