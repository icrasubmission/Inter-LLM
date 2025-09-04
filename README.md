
# Codes for Interleaved LLM and Motion Planning

## Prerequisite

1. **General Environment**

   Ubuntu 20.04, Python 3.8

   Simulation Scene: ProcThor https://procthor.allenai.org/

   Robot Entity: ManipulaTHOR https://ai2thor.allenai.org/manipulathor/

2. **Anaconda Environment**

   (1) Install [Anaconda](https://www.anaconda.com/)

   (2) In the main folder, run `conda env create -f conda_env.yml` to install the conda environment

   (3) Run `conda activate ai2thor` to activate the installed conda environment

## Run Algorithms

1. Set the algorithm, scene_id, and LLM configurations in the `config.yaml` file

2. In the `OPENAI_API_KEY` field of the `config.yaml` file, insert you own key

3. In the main folder, run `python -m main` to evaluate the specified algorithm in the ProcThor scene
