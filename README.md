# Assembly Information Model

This repository provides datastructures, tools and methods for the modeling of discrete assemblies.

## Requirements

* COMPAS 2

## Installation COMPAS 2

### Installation COMPAS 2
(via your Anaconda Prompt, Run as Administrator)
    
    (base)  conda create -n your_env_name -c conda-forge compas
    (base)  conda activate your_env_name

### Verify Installation of COMPAS 2

    (your_env_name) python -m compas
    Yay! COMPAS is installed correctly!   

### Installation COMPAS 2 on Rhino from PyPI

    (your_env_name) python -m compas_rhino.print_python_path
    (your_env_name) C:\Users\your_user_name\.rhinocode\py39-rh8\python.exe -m pip install compas

## Installation Assembly Information Model 2

### Cloning of repository

Clone the [assembly_information_model_2](https://github.com/augmentedfabricationlab/assembly_information_model_2) repository.

### Option 1: Installation in final mode

    (your_env_name) pip install -r requirements-dev.txt  
    (your_env_name) invoke add-to-rhino  
    (your_env_name) pip install your_filepath_to_assembly_information_model

### Option 2: Installation in editable mode

    (your_env_name) pip install -e your_filepath_to_assembly_information_model

### Make it accessible in Rhino

* Type ScriptEditor in the Rhino Command line
* Go to Tools --> Options --> Python 3 --> Module Search Paths and add the src folder of your_filepath_to_assembly_information_model to the path





## Credits

This package was created by [Kathrin Doerfler](doerfler@tum.de) [@kathrindoerfler](https://github.com/kathrindoerfler) at [@augmentedfabricationlab](https://github.com/augmentedfabricationlab). This package is based on [compas_assembly](https://github.com/BlockResearchGroup/compas_assembly) by [@BlockResearchGroup](https://github.com/BlockResearchGroup)


