# Tensorflow VScode Remote - Development Container for developing and training Tensorflow models

[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://tensorflow.org)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

[![GitHub license](https://img.shields.io/badge/License-MIT%20License-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Thehunk1206/Tensorflow-dev-container?style=social)](https://github.com/Thehunk1206/Tensorflow-dev-container/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Thehunk1206/Tensorflow-dev-container?style=social)](https://github.com/Thehunk1206/Tensorflow-dev-container/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/Thehunk1206/Tensorflow-dev-container?style=social)](https://github.com/Thehunk1206/Tensorflow-dev-container/watchers)

[![Github](https://img.shields.io/badge/Github-black?style=flat&logo=github)](https://github.com/Thehunk1206/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/tauhid-khan-24bb45177/)
![Twitter](https://img.shields.io/twitter/follow/KhanTauhid8?style=social)
[![Gmail](https://img.shields.io/badge/Gmail-mail2tauhidkhan@gmail.com-red?style=flat&logo=gmail)](mailto:mail2tauhidkhan@gmail.com)

A Development container configuration files or "definitions" for developing and training [Tensorflow](https://tensorflow.org) models using VScode [Remote - Container](https://aka.ms/vscode-remote/download/containers) extension.

* Lets you develope and train Tensorflow models in a container, without any hustle of installing Tensorflow and other dependencies on your local machine.
* Supports both CPU and GPU based Tensorflow models. To use Tesorflow-GPU, change the build argument in `.devcontainer/devcontainer.json` file from `TAG=2.X.X` to `TAG=2.X.X-gpu` and rebuild the container.(NOTE: Tensorflow-GPU is not tested, if anyonne has GPU on their machine do try it and update the repo.)
* Creates a typical Tensorflow project directory structure in the container.
* The container includes zsh as default shell.

## Prerequisites
+ [Docker Runtime](https://docs.docker.com/get-docker/)
+ [VScode](https://code.visualstudio.com/download)
+ [Remote - Container](https://aka.ms/vscode-remote/download/containers) extension for VScode

## Usage
* Clone this repository using command ```git clone https://github.com/Thehunk1206/Tensorflow-dev-container.git``` or use this [template](https://github.com/Thehunk1206/Tensorflow-dev-container/generate) to create your own repository on github.
* Change dir into clone folder by `cd Tensorflow-dev-container/`
* Open the folder in VS Code `code .`
* Install [remote-container](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) extention from vscode extension marketplace.
* Once Extension is install, Click 'Re-open in container' when prompt OR to open manually, press F1 and type `Remote-Container:Rebuild and Reopen in container`
* Wait to build and open the image and container. (This may take while for the first time.)
* If you want to install some python dependencies during build, add them in `.devcontainer/requirements.txt`

## Reference
Do check the [flutter-dev-container](https://github.com/predatorx7/flutterv2-vscode-devcontainer) for flutter developers
