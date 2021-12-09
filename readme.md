
# GIRAFFE

## Representing Scenes as Compositional Generative Neural Feature

### CS-584 - Illinois Tech

* Nils Chol
* Tim Girard

Note: npz files (representing numpy arrays) are excluded from this repository as they are over 100mb in size 


Commands to execute code

conda env create -f environment.yml
conda activate giraffe

To train a dataset
python train.py dataset.yaml the dataset name is in the "Configs"

to render a dataset 
python render.py dataset_pretrained.yaml the dataset name is in the "Configs"
to evaluate a dataset 
python eval.py dataset_pretrained.yaml the dataset name is in the "Configs"
