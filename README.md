# In Vivo Imaging and Physiological Modelling - BMED 360 Spring 2020

## ( with [_ad hoc_](./outbreak-science/README_outbr_sci.md) curriculum* on COVID-19 and "outbreak science" )

[Work in progress ver. 20200421]

![BMED360 image](./assets/bmed360_logo.png)

This is the repository for the course [BMED360](https://www.uib.no/en/course/BMED360) given at the Department of Biomedicine<br>

Biomedicine covers those areas of human biology, chemistry and medicine that seek to explain the factors behind health and disease at the molecular and cellular level. This information is applied in the development of better diagnostics and treatments.<br>

In this repository you find presentations, documentation, code, and partly data for the course.

The goal of this course is to obtain theoretical and practical knowledge on functional and quantitative in vivo imaging in man and animal using magnetic resonance imaging (MRI) and computer-based image analysis. The focus is on brain imaging (perfusion, diffusion, permeability mapping) and structural and functional connectivity, but also examples from functional kidney imaging and (image-based) systems biology will be presented. A major objective is also to give insight about the importance of mathematical models and computations in analysis and understanding of complex physiological processes, and the need of cross-disciplinary collaborations.



***) <br>We plan to run BMED 360 (8 students enrolled) starting April 21 ("fully digitized") with a slightly modified curriculum, also addressing COVID-19 and "outbreak science" from a computional imaging and modeling perspective. There will be online slides, computer labs (code and data on GitHub,  using issue tracker for student interaction), assignments/challenges, digital MCQ, and a final digital oral exam from home (presenting yor personal project on Google hangouts / Zoom / Skype - taking load from MittUiB, mostly used for static information). Grading has been A-F, this semester we will use pass/nopass. <br>This is work in PROGRESS . . .**



You will find more (static) information about
this course at [MittUiB](https://mitt.uib.no/courses/22178)




# Setting up your system (preparation to the course)

**Follow the instructions at [Setting up your system](setup.md) (`setup.md`) to get ready**

### Browser
- Display and functionality might differ between browsers - we recommend using Google [Chrome](https://www.google.com/chrome) on all platforms

# Notebooks
The course is based on the Jupyter Notebook, a web-based framework for developing and presenting code-based projects (take a look at https://youtu.be/HW29067qVWk og https://youtu.be/2eCHD6f_phE for introductions to Jupyter Notebooks).

## IMPORTANT (for making your own coding experiments without conflict with the original notebooks)
Throughout the course you will work with notebooks that contain various material and programming tasks. We recommend that you *make a copy of our notebooks before you are editing them*. In this respect you might adopt the naming convention `my_[name_of_notebook].ipynb`. Remember also to start a new session with a `git pull` (things can have changed).


## Get started - test your environment
* [Python, Numpy, Pandas, Matplotlib, Nibabel, Biopython and more](notebooks/0.0-test.ipynb): run through this notebook (`test-notebooks/0.0-test.ipynb`) to check that your environment is OK.<br>



## Major topics in the "In Vivo Imaging and Physiological Modelling" course:


**LECTURES**:

- **Lec 0: [Course overview](https://docs.google.com/presentation/d/1VZ82RAl2TxBh88FvWEl9K6W1Dcacw1BA32bILS1T-XI/edit?usp=sharing); [SW installation](setup.md); Motivation:** [Can a biologist fix a radio?](https://www.cell.com/cancer-cell/pdf/S1535-6108(02)00133-2.pdf) Lazebnic (2002); [Why programming?](https://drive.google.com/file/d/1Zss5kTEgVmoF8PxQpho2yvfNviJOksgv); Why top-down? - [teaching "the whole game"](https://www.fast.ai/2016/10/08/teaching-philosophy) (see also https://computingskillsforbiologists.com)
- **Lec 1**: _Introduction to modelling, MRI, and image processing_;  **BROWSE through**: [Tofts (2018) Ch. [1](https://drive.google.com/open?id=1s36p4vEXEEfmL3KZqMaHkbu4e58XMgDj), Ch. [2](https://drive.google.com/open?id=1zWhdLIzTFsk92a-XLWj7eW8pHmDs5VEG), Ch. [17](https://drive.google.com/open?id=19U76zBL2ZQrRnhUT-s_GpFzPM29WpJLB), Ch. [18](https://drive.google.com/open?id=1t9vUUJ6Xc4zmCdCjwNJuqhZHo_CV06ad);  McRobbie (2017) Ch. [3](https://drive.google.com/open?id=1igDMEVAnWR3kU1doXTz_X-LygdVLQovJ), Ch. [4](https://drive.google.com/open?id=15_9lHA_6DXZHhQEXH2T-VLNDbV16A1zo), Ch. [5](https://drive.google.com/open?id=14TGT59koVT6ujgYNDwK5G5xOA3LFlcSI), Ch. [8](https://drive.google.com/open?id=1CiCRAslFUb5Q3DZqpbEhkdBJm57vQx4O)]
- **Lec 2**: _Water diffusion_, dMRI, and tissue microstructure - Part 1 [Tofts (2018) Ch. [8](https://drive.google.com/open?id=1rck9B5qsW0uV49D9588HolNLCRm7g9jy); McRobbie (2017) Ch. [18](https://drive.google.com/open?id=1kAUzG30nGN4a9pPq45jH6pIHPU0EKwyC) pp. 303-310.]
- **Lec 3**: _Water diffusion_, diffusion tensor imaging and beyond - Part 2 [Tofts (2018) Ch. [9](https://drive.google.com/open?id=1ZRfd4iI8q0VmfuEzPVwgkhlHawvrglf3); [Westin (2002)](https://drive.google.com/open?id=1WkAbJi3Xh4sdDdBMiu9yuXEU9UzGKKSs)]
- **Lec 4**: _Blood perfusion_ and dynamic susceptibility contrast MRI (DSC-MRI) - Part 1  [Tofts (2003) Ch. [11](https://drive.google.com/open?id=1DWhL0B8xGc1EL1Ag7J4I2iCMBdHl-2mA); McRobbie (2017) Ch. [18](https://drive.google.com/open?id=1kAUzG30nGN4a9pPq45jH6pIHPU0EKwyC) pp. 311-314.]
- **Lec 5**: _Blood perfusion_, tracer kinetics, and deconvolution - Part 2  [Tofts (2003) Ch. [11](https://drive.google.com/open?id=1DWhL0B8xGc1EL1Ag7J4I2iCMBdHl-2mA)]
- **Lec 6**: _Vascular permeability_, compartment modelling, and T1w dynamic contrast-enhanced MRI (DCE-MRI) [Tofts (2018) Ch. [14](https://drive.google.com/open?id=1Wy6ZGurLkV18q6v1XAlhMRfvLttV2f08); McRobbie (2017) Ch. [18](https://drive.google.com/open?id=1kAUzG30nGN4a9pPq45jH6pIHPU0EKwyC) pp. 316-319; Measurement of Renal Perfusion and Filtration with MRI [GitHub](https://github.com/arvidl/functional-kidney-imaging) / [slides](https://docs.google.com/presentation/d/1WS6ODHrXOfYL-fXLw847EkYR4qcvDJA6bRTvqFE_fIY/edit?usp=sharing)]
- **Lec 7**: _Brain connectivity_ assessed with aMRI, dMRI, fMRI and network (graph) theory  [Fornito (2016) Ch. [1](https://drive.google.com/open?id=179E3CAZsV6LzV7Jb37eHmczuzVLJUB4H); [Bassett (2018)](https://drive.google.com/open?id=1PW30HroQMBLPLDiZsnhJZ-obumW5RaEA); McRobbie (2017) Ch. [18](https://drive.google.com/open?id=1kAUzG30nGN4a9pPq45jH6pIHPU0EKwyC) pp. 319-325.]
- **Lec 8**: _Outbreak science and COVID-19_ [[README](./outbreak-science/README_outbr_sci.md)]

**LABS**:

- **Lab 0**: [SW installation](setup.md) and beginners-guide [[01-begin](./beginners-guide/01-begin-PythonBasicforBusydummiesOnestop.ipynb)] [[02-begin](./beginners-guide/02-begin-image_processing_basics.ipynb)] [[03-begin](./beginners-guide/03-begin-pandas-basics.ipynb)] ([prog4comp-SL-HPL](./prog4comp-SL-HPL) for going deeper)
- **Lab 1**: Data analysis, image processing, and modelling in PYTHON [[01-mri](./mri/01-mri-intro.ipynb)] [[02-mri](./mri/02-mri-multispectral.ipynb)] [[03-mri](./mri/03-mri-snr-cnr.ipynb)]
- **Lab 2**: Multispectral imaging and tissue classification ([machine learning](./machine-learning/README_ml.md)) [...] [...] [[01-ml](./machine-learning/01-intro-example.ipynb)][[02-ml](./machine-learning/02-extensive-example.ipynb)])
- **Lab 3**: Processing of diffusion MRI (dMRI / DTI)  [[DIPY](https://dipy.org)]  [[README](./diffusion/README_diff.md)]
- **Lab 4**: Processing of perfusion MRI (pMRI / DSC-MRI)  [[README](./perfusion/README_perf.md)]
- **Lab 5**: Vascular permeability mapping (DCE-MRI) [[README](./permeability/README_perm.md)]
- **Lab 6**: Outbreak science and COVID-19 (biology, epidemiology, geo-mapping, imaging)  [[README](./outbreak-science/README_outbr_sci.md)]



**ASSESSMENT / EXAM**:

- **MCQ / Quiz**: [[README](./exam/README.md)]
- **Oral presentation of PROJECT**: [[README](./exam/README.md)]



[Previous (2019) LECTURES](https://sites.google.com/site/bmed360/courses) and
[Previous (2019) LABS](https://sites.google.com/site/bmed360/labs)

**Q&A topics** (from 2019) [[gslides](https://docs.google.com/presentation/d/1-9HeVb1ewBLVVxcrh2-JRnepcPxPisZW_tgSfYVYp54/edit?usp=sharing)]


## Tentative schedule (= self-paced workflow) Spring 2020

<p>&nbsp;</p>
<div><strong>TENTATIVE order of topics and programming labs / demos (Spring 2020)</strong>:</div>
<div>
<table border="1" cellspacing="0">
<tbody>
<tr>
<td>&nbsp;BLOCK 1</td>
<td>&nbsp;Day 1 (April 21)</td>
<td>&nbsp;Lec 0, Lec 1</td>
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
<td>&nbsp;MIDTERM PROJECT</td>
<td>&nbsp;description</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;WORKING with MIDTERM</td>
<td>&nbsp;PROJECT</td>
</tr>
<tr>
<td>&nbsp;BLOCK 2</td>
<td>&nbsp;Day 11 (May 29)</td>
<td>&nbsp;Presenting MIDTERM<span>&nbsp;</span><br />&nbsp;PROJECT results&nbsp;</td>
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
