# In Vivo Imaging and Physiological Modelling v2020

![BMED360 image](./assets/bmed360_logo.png)

This is the repository for the course [BMED360](https://www.uib.no/en/course/BMED360) given at the Department of Biomedicine<br>

(*) Biomedicine covers those areas of human biology, chemistry and medicine that seek to explain the factors behind health and disease at the molecular and cellular level. This information is applied in the development of better diagnostics and treatments.<br>

Here you find code and documentation for the course.

The goal of this course is to obtain theoretical and practical knowledge on functional and quantitative in vivo imaging in man and animal using magnetic resonance imaging (MRI) and computer-based image analysis. The focus is on brain imaging (perfusion, diffusion, permeability mapping) and structural and functional connectivity, but also examples from functional kidney imaging and (image-based) systems biology will be presented. A major objective is also to give insight about the importance of mathematical models and computations in analysis and understanding of complex physiological processes, and the need of cross-disciplinary collaborations.

You will find more detailed information about
this course at [MittUiB](http://mitt.uib.no/course/17428).

# Setting up your system
CONSTRUCTION
**Follow the instructions at [Setting up your system](setup.md) (`setup.md`) to get ready**



# Notebooks
The course is based on the Jupyter Notebook, a web-based framework for developing and presenting code-based projects (take a look at https://youtu.be/HW29067qVWk og https://youtu.be/2eCHD6f_phE for introductions to Jupyter Notebooks).

Throughout the course you will work with notebooks that contain various material and programming tasks. We recommend that you *make a copy of our notebooks before you are editing them*. In this respect you might adopt the naming convention `my_[name_of_notebook].ipynb`.


## Get started - test your environment
* [Python, Numpy, Pandas, Matplotlib, Nibabel, Biopython and more](notebooks/0.0-test.ipynb): run through this notebook (`notebooks/0.0-test.ipynb`) to check that your environment is OK.<br>

_____________________________________________________________________________________________<br>

## Major topics in the "In Vivo Imaging and Physiological Modelling" course are:


[LECTURES](https://sites.google.com/site/bmed360/courses):

- **Lec 0: [Course overview](https://docs.google.com/presentation/d/1bBlf3NSL8BfmqRvN99-0hUY2Yqm5KjVgCJ3pVZw0PRA/edit?usp=sharing); [SW installation](setup.md), tools and repositories**  (see also https://computingskillsforbiologists.com)
- **Lec 1: Introduction to modelling, MRI and image processing** [[gslides](https://docs.google.com/presentation/d/1-Mfsun9_yc1xsIfeIRIT3JZHLN5r_42wuKxt9HLUa38/edit?usp=sharing)]
- **Lec 2 & 3: Water diffusion and diffusion tensor MR Imaging (MR-DTI)** [[part1](https://docs.google.com/presentation/d/1qMxwu401az5zgq6Rg5M7kOtygdeosnMeSucvy7SSbNk/edit?usp=sharing)] [[part2](https://docs.google.com/presentation/d/11Xb5AmhG0bpkK6Kx7hY99HNMudPFPCpxfkGQsIslOJM/edit?usp=sharing)]
- **Lec 4 & 5: Blood perfusion and dynamic susceptibility contrast MR imaging (DSC-MRI)** (PPT: [part1](https://drive.google.com/file/d/1BNp_34DfjU6tEAnPT_wqdIN_DxtH8Txs/view?usp=sharing)) (PPT: [part2](https://drive.google.com/file/d/1Xnvp5oTlgi7OUbF-LPBVF9N_3zf7-u94/view?usp=sharing))
- **Lec 6: Vascular permeability and T1-weighted dynamic contrast enhanced MRI (DCE-MRI)** [[gslides](https://docs.google.com/presentation/d/1EYuKHtQM4RIgkvIxrMyAkq02l8KUd9WuCsjCHviBaKI/edit?usp=sharing)]
- **Lec 7: Structural and functional brain connectivity using multimodal recordings** [[gslides](https://docs.google.com/presentation/d/142Y5wQKkIvRkcmBiSV2INDhuMdRHrpPhxqs2zx17ZCY/edit?usp=sharing)]
- **Lec 8: Special topic** (e.g. Introduction to systems biology; [On consciousness, resting state fMRI, and neurodynamics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2880806); [Deep learning in medical imaging with focus on MRI](https://www.sciencedirect.com/science/article/pii/S0939388918301181))  [[gslides](https://docs.google.com/presentation/d/1XonWZca9-qinNhdl-UOzQRGrT0KCb7EBQh1EH2kdC30/edit?usp=sharing)]


[LABS](https://sites.google.com/site/bmed360/labs):

- **Lab 1** Data analysis and image processing in PYTHON (and MATLAB) - [[0.0-test.ipynb](./notebooks/0.0-test.ipynb)], [[0.1-python.ipynb](./notebooks/0.1-python.ipynb)], [[0.2-pandas.ipynb](./notebooks/0.2-pandas.ipynb)], [[1.1-kiwi.ipynb](./notebooks/1.1-kiwi.ipynb)]
- **Lab 2** Multispectral imaging and tissue classification (machine learning; supervised and unsupervised learning) - [[1.0-mri.ipynb](./notebooks/1.0-mri.ipynb)], [[1.2-mri-dcm2niix.ipynb](./notebooks/1.2-mri-dcm2niix.ipynb)], [[2.0-mri-tissue-classification.ipynb](./notebooks/2.0-mri-tissue-classification.ipynb)]
- **Lab 3** Processing of diffusion MRI data (DTI and DSI) - [[3.0-diffusion-mri.ipynb](./notebooks/3.0-diffusion-mri.ipynb)]
- **Lab 4** Processing of dynamic susceptibility contrast MR images (DSC-MRI) [[4.0-perfusion-mri.ipynb](./notebooks/4.0-perfusion-mri.ipynb)]
- **Lab 5** Vascular permeability mapping and Dynamic T1-weighted Contrast Enhanced MRI
(DCE-MRI)
- **Lab 6** Estimation and visualization of structural and functional brain connectivity incl. complex network analysis  [[6.0-brain-connectivity-nilearn.ipynb](./notebooks/6.0-brain-connectivity-nilearn.ipynb)]

[[KIWI SEED SEGMENTATION CHALLENGE](./notebooks/1.5-mri-kiwi-seed-segmentation.ipynb)]

**Q&A topics** [[gslides](https://docs.google.com/presentation/d/1-9HeVb1ewBLVVxcrh2-JRnepcPxPisZW_tgSfYVYp54/edit?usp=sharing)]


## Tentative schedule Spring 2020

<p>&nbsp;</p>
<div><strong>Tentative order of lectures and programming labs / demos (Spring 2020)</strong>:</div>
<div>
<table border="1" cellspacing="0">
<tbody>
<tr>
<td>&nbsp;BLOCK 1</td>
<td>&nbsp;Day 1 (April 21)</td>
<td>&nbsp;Lec 1</td>
<td>&nbsp;Lab &nbsp;1</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 2 (April 22)</td>
<td>&nbsp;Lec 2</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 3 (April 23)</td>
<td>&nbsp;Lec 3</td>
<td>&nbsp;Lab 2</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 4 (April 24)</td>
<td>&nbsp;Lab 2 cont</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 5 (April 29)</td>
<td>&nbsp;Lab 3</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 6 (May 4)</td>
<td>&nbsp;Lec 4</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 7 (May 5)</td>
<td>&nbsp;Lec 5</td>
<td>&nbsp;Lab 4</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 8 (May 6)</td>
<td>&nbsp;Lec 6</td>
<td>&nbsp;Lab 5</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 9 (May 11)</td>
<td>&nbsp;Lec 7</td>
<td>&nbsp;Lab 6</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 10 (May 12)</td>
<td>&nbsp;Home prj</td>
<td>&nbsp;present</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;HOME<br />PROJECT</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;BLOCK 2</td>
<td>&nbsp;Day 11 (May 29)</td>
<td>&nbsp;Home<span>&nbsp;</span><br />project results&nbsp;</td>
<td>&nbsp;Lec 8</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 12 (June 2)</td>
<td>&nbsp;Exam<br />&nbsp;prep.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 13 (June 3)</td>
<td>&nbsp;Q &amp; A</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 14 (June 4)</td>
<td>&nbsp;Exam<br />&nbsp;&nbsp;prep.</td>
<td>&nbsp;MC /<br />&nbsp;quiz<br />&nbsp;exam</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 15 (June 5)</td>
<td>Oral exam</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
</div>
<p>&nbsp;</p>


<!--

**[[Schedule](https://docs.google.com/presentation/d/1QmLPof1lMRLO7JJ7fk_dvqsJUQ89pBKZNwDXy6V20rM/edit?usp=sharing)] for Block2 (June 3-7, 2019)**

<p>&nbsp;</p>
<div><strong>Order of lectures and programming labs / demos (tentative schedule Spring 2019)</strong>:</div>
<div>
<table border="1" cellspacing="0">
<tbody>
<tr>
<td>&nbsp;BLOCK 1</td>
<td>&nbsp;Day 1 (April 24)</td>
<td>&nbsp;Lec 1</td>
<td>&nbsp;Lab &nbsp;1</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 2 (April 26)</td>
<td>&nbsp;Lec 2</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 3 (April 29)</td>
<td>&nbsp;Lec 3</td>
<td>&nbsp;Lab 2</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 4 (April 30)</td>
<td>&nbsp;Lab 2 cont</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 5 (May 3)</td>
<td>&nbsp;Lab 3</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 6 (May 6)</td>
<td>&nbsp;Lec 4</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 7 (May 7)</td>
<td>&nbsp;Lec 5</td>
<td>&nbsp;Lab 4</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 8 (May 8)</td>
<td>&nbsp;Lec 6</td>
<td>&nbsp;Lab 5</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 9 (May 13)</td>
<td>&nbsp;Lec 7</td>
<td>&nbsp;Lab 6</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 10 (May 14)</td>
<td>&nbsp;Home prj</td>
<td>&nbsp;present</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;HOME<br />PROJECT</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;BLOCK 2</td>
<td>&nbsp;Day 11 (June 3)</td>
<td>&nbsp;Home<span>&nbsp;</span><br />project results&nbsp;</td>
<td>&nbsp;Lec 8</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 12 (June 4)</td>
<td>&nbsp;Exam<br />&nbsp;prep.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 13 (June 5)</td>
<td>&nbsp;Q &amp; A</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 14 (June 6)</td>
<td>&nbsp;Exam<br />&nbsp;&nbsp;prep.</td>
<td>&nbsp;MC /<br />&nbsp;quiz<br />&nbsp;exam</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 15 (June 7)</td>
<td>Oral exam</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
</div>
<p>&nbsp;</p>

-->
