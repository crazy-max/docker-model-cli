# docker model

<!---MARKER_GEN_START-->
Docker Model Runner (EXPERIMENTAL)

### Subcommands

| Name                                            | Description                                                                                                            |
|:------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| [`inspect`](model_inspect.md)                   | Display detailed information on one model                                                                              |
| [`install-runner`](model_install-runner.md)     | Install Docker Model Runner (Docker Engine only).                                                                      |
| [`list`](model_list.md)                         | List the models pulled to your local environment                                                                       |
| [`logs`](model_logs.md)                         | Fetch the Docker Model Runner logs                                                                                     |
| [`package`](model_package.md)                   | Package a GGUF file into a Docker model OCI artifact, with optional licenses, and pushes it to the specified registry. |
| [`pull`](model_pull.md)                         | Pulls a model from Docker Hub or HuggingFace to your local environment                                                 |
| [`push`](model_push.md)                         | Push a model to Docker Hub                                                                                             |
| [`rm`](model_rm.md)                             | Remove local models downloaded from Docker Hub                                                                         |
| [`run`](model_run.md)                           | Run a model and interact with it using a submitted prompt or in chat mode                                              |
| [`status`](model_status.md)                     | Check whether the Docker Model Runner is running                                                                       |
| [`tag`](model_tag.md)                           | Tag a model                                                                                                            |
| [`uninstall-runner`](model_uninstall-runner.md) | Uninstall Docker Model Runner                                                                                          |
| [`version`](model_version.md)                   | Show the Docker Model Runner version                                                                                   |


### Options

| Name                | Type     | Default                  | Description                                                                                                                           |
|:--------------------|:---------|:-------------------------|:--------------------------------------------------------------------------------------------------------------------------------------|
| `--config`          | `string` | `/root/.docker`          | Location of client config files                                                                                                       |
| `-c`, `--context`   | `string` |                          | Name of the context to use to connect to the daemon (overrides DOCKER_HOST env var and default context set with "docker context use") |
| `-D`, `--debug`     | `bool`   |                          | Enable debug mode                                                                                                                     |
| `-H`, `--host`      | `list`   |                          | Daemon socket to connect to                                                                                                           |
| `-l`, `--log-level` | `string` | `info`                   | Set the logging level ("debug", "info", "warn", "error", "fatal")                                                                     |
| `--tls`             | `bool`   |                          | Use TLS; implied by --tlsverify                                                                                                       |
| `--tlscacert`       | `string` | `/root/.docker/ca.pem`   | Trust certs signed only by this CA                                                                                                    |
| `--tlscert`         | `string` | `/root/.docker/cert.pem` | Path to TLS certificate file                                                                                                          |
| `--tlskey`          | `string` | `/root/.docker/key.pem`  | Path to TLS key file                                                                                                                  |
| `--tlsverify`       | `bool`   |                          | Use TLS and verify the remote                                                                                                         |


<!---MARKER_GEN_END-->

## Description

Use Docker Model Runner to run and interract with AI models directly from the command line.
For more information, see the [documentation](https://docs.docker.com/model-runner/)

