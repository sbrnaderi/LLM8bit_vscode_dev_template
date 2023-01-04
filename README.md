# LLM8bit_vscode_dev_template
This repo is a starting point for those who want to create a Dev Container to use the [bitsandbytes](https://github.com/TimDettmers/bitsandbytes) library in their vscode project. 

## Motivation
I was trying to use the bitsandbytes library on windows WSL and I encounter an issue with the library not recognizing my CUDA installation. So, I decided to create a docker dev container and start from a clean Pytorch installation with CUDA in docker.

In general, having a dev container is useful, because one can store all their run configurations in a file that can be reused later on other machines (regardless of whether it is a Linux machine or a windows WSL machine). 

## Installation
You only need to make sure that docker is installed on your system and it has access to GPU/s. After this, you can start vscode and clone this repo (or use it as a template) and open your project in Dev Container. See [this](https://code.visualstudio.com/docs/devcontainers/tutorial). 
