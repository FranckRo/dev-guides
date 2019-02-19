[Home](../README.md) - [NPM](../docs/npm.md) - [Unix](../docs/unix-commands.md) - [Windows](../docs/windows.md) - [Maven](../docs/maven.md)

| Command |    Description  |
| ------------- |: -------------: |
| <code>docker ps </code> | List all running processus |
| <code>docker logs processId|processName </code> | Show logs for the process identified by name or processus id  |
  <code>docker logs -f --tail 200 processId|processName </code> | Show logs for the process identified by name or processus id |
  <code>docker system prune </code> | Remove stopped containers, not used networks, dangling cache or images. Before docker v 17.06, volumes were also pruned. Since, we have to specify the --volumes flag|
  

