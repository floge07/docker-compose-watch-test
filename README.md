[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=git@github.com:floge07/docker-compose-watch-test.git)

#### Click the button above, or do these steps:
1. Open Visual Studio Code
2. Use the command `Dev Containers: Clone Repository in Container Volume...` and enter the repository url into the input field (ignore the dropdown).

#### After that everything should work out of the box.

Just open a terminal and execute `deploy.sh`, which should fail with the following error:

```
cannot take exclusive lock for project "test-project-watch": could not create any of the following paths: /run/user/1000
```