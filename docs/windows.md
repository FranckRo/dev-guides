[Home](../README.md) - [NPM](../docs/npm.md) - [Unix](../docs/unix-commands.md) - [Windows](../docs/windows.md) - [Maven](../docs/maven.md)

| Command |    Description  |
| ------------- |: -------------: |
| <code>rd /S /Q path </code> | Delete without asking (/Q) all subdirectories and files (/S) from the given path |

#### How to iterate over a specific search (made in a terminal f. ex.) in a .bat file
```
SET cmd="dir /A:D/B/D %SEARCH_LOCATION% | findstr "yourSearch"
FOR /F %%d in ('%cmd%') DO (
  echo %SEARCH_LOCATION%\%%d
)
```