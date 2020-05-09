# In Vivo Imaging and Physiological Modelling - BMED 360 Spring 2020

### _connectivity_


## Software for network science

- An `awesome list` of resources to construct, analyze and visualize network data - https://github.com/briatte/awesome-network-analysis

- Jupyter notebooks developed and used by [Erika Fille Legara](https://erikalegara.site) in her Network Science class -  https://github.com/eflegara/Network-Science-Lectures





NOTE: [`Awesome list`](https://github.com/sindresorhus/awesome) is a concept developed by Sindre Sørhus (Norway) of awesome stuff curated in a list.

## Software for functional MRI and brain connectivity

-  Brain Imaging Analysis Kit (BrainIAK) [[GitHub](https://github.com/brainiak/brainiak)] [[Docs](https://brainiak.org/docs)] [[Tutorials](https://brainiak.org/tutorials)] and  **paper**: Kumar M et al. BrainIAK tutorials: User-friendly learning materials for advanced fMRI analysis. PLoS Computational Biology 2020;16(1), e1007549  [[link](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007549)] [[pdf](https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1007549&type=printable)]

How to install a separate `brainiak` conda environment and the `BrainIAK` software kit (NOTE: Windows not supported):

> conda info --envs<br>
> conda deactivate<br>
> conda create --name brainiak python=3.7<br>
> conda activate brainiak<br>
> conda install -c brainiak -c defaults -c conda-forge brainiak<br>
> conda install -n brainiak ipykernel<br>
> python -m ipykernel install --user --name brainiak --display-name "BRAINIAK"<br>


