# Part 1: The building blocks of neural networks

A quick introduction to the building blocks of neural networks, and the construction and training of neural networks in PyTorch.

## Structure

```
├── LICENSE
├── README.md               <- The top-level README file
├── data                    <- Data used in the examples
├── nbs                     <- Jupyter notebooks. 
├── environment-gpu.yml     <- The requirements file for reproducing the Python environment, GPU version
└── environment-cpu.yml     <- The requirements file for reproducing the Python environment, CPU version
``` 

## Slides

_The slides accompanying Part 1 will be added_

## Notebooks

_Notebooks TBA_

| Notebook    |      1-Click Notebook      |
|:----------|------|
|  [1.0-asl-nnets_building_blocks_part1.ipynb](https://nbviewer.org/github/MMIV-ML/HVL-MMIV-DLN-AI-2022/blob/master/1-deep_learning/nbs/1.0-asl-nnets_building_blocks_part1.ipynb)  | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/HVL-MMIV-DLN-AI-2022/blob/master/1-deep_learning/nbs/1.0-asl-nnets_building_blocks_part1.ipynb)
| [2.0-asl-nnets_building_blocks_part2.ipynb](https://nbviewer.org/github/MMIV-ML/HVL-MMIV-DLN-AI-2022/blob/master/1-deep_learning/nbs/1.0-asl-nnets_building_blocks_part2.ipynb)  | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/HVL-MMIV-DLN-AI-2022/blob/master/1-deep_learning/nbs/1.0-asl-nnets_building_blocks_part2.ipynb)|


## Run locally

Install the necessary libraries:

If you have a PyTorch compatible GPU, then install 

```bash
conda env update -f environment-gpu.yml
```

If you want to use a CPU:

```bash
conda env update -f environment-cpu.yml
```


Install a Jupyter kernel:
```bash
conda activate pytorch
python -m ipykernel install --user --name pytorch --display-name "PyTorch"
conda deactivate
``` 

Finally, launch Jupyter Notebook or Jupyter Lab.