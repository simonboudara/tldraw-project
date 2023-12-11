# Tldraw Project

![Tldraw](images/hello-tldraw.png)

## Quickstart

 0. [Install the pixi package manager](https://pixi.sh/#installation).

 1. [Fork this github repository](https://github.com/boisgera/tldraw-project/fork).

 2. Download its content on your computer.

 3. Open a terminal in the project root folder and type `pixi run start`.

## Troubleshooting

If for some reason pixi doesn't work for you, you will need a bit more work.

Read the contents of [`pixi.toml`](pixi.toml):

  - The `[dependencies]` section contains the conda-forge packages that the 
    project needs. 
    
    Install them with `conda`.

  - The `[pypi-dependencies]` section contains the Pypi packages that the 
    project needs. 
    
    Install them with `pip`.

  - The `[tasks]` section tells you what happens when you call `pixi run` 
    followed by the name of a task. 
    
    Here `pixi run start` invokes `jupyter lab` 
    in an environment where the conda-forge and Pypi dependencies are met.