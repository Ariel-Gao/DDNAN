<h4 align="center">DDNAN: Knowledge Graph Embedding with 
Direct and Disentangled Neighborhood
Representation Attention Network</h4>

<h2 align="center">
  Architecture of DDNAN
  <img align="center"  src="./fig/DDNAN-model.png" alt="...">
</h2>

This is our PyTorch implementation for the paper DDNAN. (Current implementation is not complete, it will be updated in the future)

### Training model:

- Fitst checkout dependencies installation in `requirements.txt.`

- pytorch=1.8, python=3.7

- `sh ./preprocess.sh` for preprocessing the dataset and setting up for experiments.

- Commands for reproducing the reported results on link prediction:
  
  ```shell
  ##### For training and test:
  python run.py -epoch 1500 -name InteractE_FB15k_K3_D200_club_b_mi_drop -mi_train -mi_drop
  ```

## Acknowledgement

The project is built upon [COMPGCN](https://github.com/malllabiisc/CompGCN)

Please create an issue or send an email to contact use.
