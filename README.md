# HoWCoM 2023 - Collaboration and Versioning Framework

This repository contains the artifacts provided for the HoWCoM 2023 MODELS Workshop. 

## File description
- `framework.xml` contains the complete feature model as presented in the paper. This file can directly opened in [FeatureIDE (> v3.9.3)](https://featureide.github.io/)
- `framework.uvl` contains the complete feature model in the novel *universal variablity language* (UVL). This model needs some more files in order to be opened correctly in FeatureIDE:
    - `submodules/*`: Some parts of the feature model are outsourced in so-called submodules for a better reuse. 
    - `.profiles/To Be Deleted.profile`: this file contains the color information for all constraints. For some reason, it must be named like this!?
- `framework.pdf`: PDF with the complete feature model and the constraints for each main-subtree side-by-side. 
- `configurations/*`: This directory contains the configurations as presented in the paper. 
- `configurations.pdf`: PDF with the configurations in a comparison table. 
- `index.html`: The main entrypoint of the interactive website that allows the generation of configurations. The following files are needed by the website to work: 
    - `alternative.svg`, `or.svg`: just two icons used in the feature tree.
    - `framework.xml`: this file is directly used by the website to build up the feature tree. 
    - `js/*`: needed javascript modules for the generation of the featuretree and the interactive analysis of the current configuration according to the cross tree constraints. 

## Interactive Configurator
At https://sp-uulm.github.io/howcom23-collaboration-and-versioning-framework/ the interactive configurator is up and running and can be directly used. 