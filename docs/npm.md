[Home](../README.md) - [NPM](../docs/npm.md) - [Unix](../docs/unix-commands.md) - [Windows](../docs/windows.md) - [Maven](../docs/maven.md)

| Command |    Description  |
| ------------- |: -------------: |
| <code>npm config get registry </code> | Get the registry of your .npmrc |
| <code>npm login </code> | Connect to the default repository |
| <code> npm login --registry=https://yourrepository.com </code> | Connect to a specific repository. This can be useful if you manage multiples registries (public, private, etc.) and if you want to publish a specific module on a private repository. |
| <code><code> npm publish </code></code> | Publish a component. The package.json of your module can contains a "publishConfig" attribute to specify a specific registry (overwrite the default registry of your .npmrc) |


