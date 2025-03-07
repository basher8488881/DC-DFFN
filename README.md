### DC-DFFN: Densely Connected Deep Feature Fusion Network with Sign Agnostic Learning for Implicit Shape Representation 


## Reconstruction Preview
![plot](https://github.com/basher8488881/DC-DFFN/blob/master/sofa1.png)


## Environment
The code is implemented and  tested on Ubuntu 20.4 linux environment. 

## Generation 

``cd ./code``  

``python evaluate/eval.py --expname shapenet --parallel --exps_folder_name trained_models --timestamp 2022_08_19_16_19_30 --checkpoint 1500 --conf ./confs/shapenet_vae.conf --split ./confs/splits/shapenet/shapenet_sofa_test_files.conf --resolution 100``

## Training 
``cd ./code`` 

``python training/exp_runner.py --parallel`` 

## Citation 
If you use this code in your research, please cite the following paper:

``@article{basher2023dc,
title={DC-DFFN: Densely Connected Deep Feature Fusion Network With Sign Agnostic Learning for Implicit Shape Representation},
  author={Basher, Abol and Boutellier, Jani},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE}
}``
## Acknowledgement 
This code is based on SALD (https://github.com/matanatz/SALD), thanks for this wonderful work. 
