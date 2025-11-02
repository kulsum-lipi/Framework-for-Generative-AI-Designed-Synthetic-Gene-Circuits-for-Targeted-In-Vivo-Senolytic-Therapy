
# Senolytic AI - Paper 4: Senescence Detection

## Project Mission
Design a computational framework that uses **generative AI** to create safe, programmable gene circuits capable of **detecting and eliminating senescent cells in vivo**.  
This enables precision senolytic therapies that selectively remove harmful, aging cells without damaging healthy ones — a key step toward next-generation treatments for aging, fibrosis, and age-related diseases.

## Core Software Stack
- **Machine Learning & Generative Design**: PyTorch, Hugging Face Transformers, Diffusers, PyTorch Lightning  
- **Synthetic Biology & Circuit Simulation**: Cello, BioCRNpyler, Tellurium, gillespy2, DNAplotlib  
- **Senescence Signature Mining**: Scanpy, scVI-tools, MEME Suite, JASPAR, gseapy  
- **Safety & Off-Target Analysis**: DeepBind, Enformer, Basenji, burden simulators  
- **DevOps & Reproducibility**: Hydra, MLflow, DVC, Git, Docker

## Folder Structure
- `notebooks/` : Analysis notebooks for EDA, labeling, and baseline experiments  
- `docs/`      : Project documentation, project charter, safety rubric, pipeline diagrams  
- `README.md`  : This file describing the project, structure, and usage  

## How to Use
1. Open notebooks in **Google Colab** or **VS Code**.  
2. Follow the steps in notebooks for **data preprocessing, labeling, and model training**.  
3. Store datasets in `docs/` or a dedicated `data/` folder (to be created if needed).

## Acknowledgements
- Public scRNA-seq and spatial datasets for senescence research  
- Paper 4 project team and advisors
