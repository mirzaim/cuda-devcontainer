# CUDA Development Container
This repo configures a CUDA development container. 
It packages all you need to build and test CUDA projects in a Linux environment. 
If you are unfamiliar with development containers, check out [this page](https://github.com/microsoft/vscode-dev-containers).

## Configuration
While the definition itself works unmodified, you can select the version of CUDA and Ubuntu the container 
uses by updating the `CUDA_VERSION` and `VARIANT` respectively in the included `devcontainer.json` 
(and rebuilding if you've already created the container). The CUDA and Ubuntu version 
has to match with image tags found [here](https://hub.docker.com/r/nvidia/cuda).
```
"args": { "VARIANT": "ubuntu20.04", "CUDA_VERSION": "11.6.0" }
```
