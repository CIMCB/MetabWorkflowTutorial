<img src="images/logo_text.png" style="width: 160px; float: right;">

# README.md - `SI_Mendez_etal_2019`   

<p align="justify">
This repository contains the supplementary information for the his repository contains the supplementary information for the "Toward Collaborative Open Data Science in Metabolomics using Jupyter Notebooks and Cloud Computing" tutorial review. The focuses is on experiential learning using an example interactive metabolomics data analysis workflow deployed using a combination of Python, Jupyter Notebooks and Binder. The three-step pedagogical process of understanding, implementation, and deployment is broken down into 5 tutorials.
</p>

<p align="justify">
The tutorials takes you through the process of using interactive notebooks to produce a shareable, reproducible data analysis workflow that connects the study design to reported biological conclusions in an interactive document. The workflow implemented includes a discrete set of interactive and interlinked procedures: data cleaning, univariate statistics, multivariate machine learning, feature selection, and data visualisation. 
</p>

<br />
    
## Quick Start

#### *To launch the tutorial environment in the cloud:* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cimcb/MetabWorkflowTutorial/master)

#### Tutorial 1:
-  [Tutorial 1 static notebook](https://cimcb.github.io/MetabWorkflowTutorial/Tutorial1.html)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CIMCB/MetabWorkflowTutorial/master?filepath=Tutorial1.ipynb)

#### Tutorial 2:
-  [Tutorial 2 static notebook](https://cimcb.github.io/MetabWorkflowTutorial/Tutorial2.html)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CIMCB/MetabWorkflowTutorial/master?filepath=Tutorial2.ipynb)

#### Tutorial 4:
-  [Tutorial 4 static notebook](https://cimcb.github.io/MetabSimpleQcViz/Tutorial4.html)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cimcb/MetabSimpleQcViz/master?filepath=Tutorial4.ipynb)

<br />

## Tutorials

1.	[Launching and using a Jupyter notebook on Binder](#one)
2.	[Interacting with and editing a Jupyter notebook on Binder](#two)
3.	[Downloading and installing a Jupyter notebook on a local machine](#three)
4.	[Creating a new Jupyter notebook on a local computer](#four)
5.	[Deploying a Jupyter notebook on Binder via GitHub](#five)

<br />

<a id="one"></a>
## Tutorial 1: Launching and using a Jupyter notebook on Binder
<p align="justify">
<i>In this tutorial we will step though a metabolomics computational workflow that has already been implemented as a Jupyter Notebook and deployed on Binder. In this workflow we will interrogate a published  <a href="https://www.nature.com/articles/bjc2015414">(Chan et al., 2016)</a> NMR urine data set (deconvolved and annotated) used to discriminate between samples from gastric cancer and healthy patients. The data set is available in the <a href="http://www.metabolomicsworkbench.org">Metabolomics Workbench data repository</a> (Project ID PR000699). The data can be accessed directly via its project <a href="http://dx.doi.org/DOI:10.21228/M8B10B">DOI:10.21228/M8B10B</a>.</i>
</p>

<p align="justify"> <i>Prior to beginning this tutorial, it is recommended to view the provided static version of the <code>Jupyter</code> analysis notebook: <a href="https://cimcb.github.io/MetabWorkflowTutorial/Tutorial1.html">Tutorial 1: Static Notebook</a></i>
</p>

#### Tutorial 1 steps:
1. Launch Binder by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cimcb/MetabWorkflowTutorial/master)
2. Click on the Tutorial1.ipynb filename to open the Jupyter Notebook
3. Run the code cells:  
    3.1. Click anywhere within the cell, which will then be outlined by a green box (or blue for text cells)  
    3.2. Click on the “Run” button in the top menu to execute the code in the cell    
4. **Alternatively**, run multiple cells:  
    4.1. In the "Cell" menu item, choose "Run All" (runs all cells in the notebook, from top to bottom)  
    4.2. In the "Cell" menu item, choose "Run all below" (runs all cells below the current selection) 
5. Download notebook (as changes to the notebook are lost when the Binder session end):  
    5.1. Return to Jupyter landing page, by choosing "File" then "Open.."  
    5.2. Click the checkbox next to each file you wish to download  
    5.3. Click the ‘Download’ button from the top menu  

<br />

<a id="two"></a>
## Tutorial 2: Interacting with and editing a Jupyter notebook on Binder
<p align="justify"><i>
The fuctionality of the notebook in Tutorial 2 is identical to Tutorial 1, but now the text cells have been expanded into a comprehensive interactive tutorial. Text cells with a yellow background provide the metabolomics context and describe the purpose of the code in the following code cell. Additional coloured text boxes are placed throughout the workflow to help novice users navigate and understand the interactive principles of a Jupyter Notebook:
</i></p>

| Box           | Description   | Purpose  |
| ------------- | ------------- | -----|
| Action  | red background labelled with ‘gears’ icon | Suggestions for changing the functionality of the subsequent code cell by editing (or substituting) a line of code |
| Interaction  | green background with ‘mouse’ icon      |   Suggestions for interacting with the visual results generated by a code cell |
| Notes | blue background with ‘lightbulb’ icon      |    Further information about the theoretical reasoning behind the block of code or a given visualisation |

<p align="justify">
<i>There is a second data included with this  tutorial which has been converted to our standardised <a href="https://en.wikipedia.org/wiki/Tidy_data">Tidy Data</a> This data has been previously published as an article <a href="https://link.springer.com/article/10.1007%2Fs11306-016-1059-9">Gardlo et al. (2016)</a>, in  Metabolomics. Urine samples collected from newborns with perinatal asphyxia were analysed, and the deconvoluted and annotated file is deposited at the <a href="https://www.ebi.ac.uk/metabolights/">Metabolights</a> data repository (Project ID <a href="https://www.ebi.ac.uk/metabolights/MTBLS290">MTBLS290</a>). </i>
</p>
 
<p align="justify">
<i>Prior to beginning this tutorial, it is recommended to view the provided static version of the <code>Jupyter</code> analysis notebook: <a href="https://cimcb.github.io/MetabWorkflowTutorial/Tutorial2.html">Tutorial 2: Static Notebook</a></i>
</p>

#### Tutorial 2 steps:
1. Launch Binder by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cimcb/MetabWorkflowTutorial/master)
2. Click on the Tutorial2.ipynb filename to open the Jupyter Notebook
3. Run the code cells:  
    3.1. Click anywhere within the cell, which will then be outlined by a green box (or blue for text cells)  
    3.2. Click on the “Run” button in the top menu to execute the code in the cell 
4. **Modify and run code cells**:  
    4.1. When prompted, complete one (or multiple) modifications suggested in each ‘action’ box .   
    4.2. Click “Run all below” from the “Cell” dropdown menu, observing the changes in cell output for all the subsequent  cells. 
5. Download notebook (as changes to the notebook are lost when the Binder session end):  
    5.1. Return to Jupyter landing page, by choosing "File" then "Open.."  
    5.2. Click the checkbox next to each file you wish to download  
    5.3. Click the ‘Download’ button from the top menu  

**Note: Further guidance for step 4 is included in the notebook itself.**

<br />

<a id="three"></a>
## Tutorial 3: Downloading and installing a Jupyter notebook on a local machine.
<p align="justify">
<i>For Tutorial 3, we will provide the process of installing Python and Jupyter, and reproducing Tutorial 1 on your own machine. The Anaconda distribution provides a unified, platform-independent framework for running notebooks and managing Conda virtual environments that is consistent across multiple operating systems, so for convenience we will use the Anaconda interface in these tutorials.</i>
</p>

#### Tutorial 3 steps:

##### Part A) Install Jupyter and Python using Anaconda

1. Go to the [Official Anaconda Website](https://www.anaconda.com/distribution/) and click the 'Download' button. 
2. Press the 'Download' button under the 'Python 3.x version' in Bold to download the graphical installer for your OS. 
3. After the download has finished, open (double-click) the installer to begin installing the Anaconda Distribution
4. Follow the prompts on the graphical installer to completely install the Anaconda Distribution

##### Part B) Create a virtual Environment, and start Tutorial 1.

**Note: If you are using Windows, you need to install git using the following: [Git for Windows](https://gitforwindows.org/)**

1. Open Terminal on Linux/MacOS or Command Prompt on Windows
2. Enter the following into the console (one line at a time)

```console
git clone https://github.com/cimcb/MetabWorkflowTutorial
cd MetabWorkflowTutorial
conda env create -f environment.yml
conda activate MetabWorkflowTutorial
jupyter notebook
```

<br />

<a id="four"></a>
## Tutorial 4: Creating a new Jupyter notebook on a local computer
<p align="justify">
<i>The Jupyter notebook we will generate for this data set demonstrates the use of visualisation methods available in Anaconda Python without the need to install additional 3rd party packages. This tutorial is made available in the GitHub repository at https://github.com/cimcb/MetabSimpleQcViz. In the notebook, we will load the data set and produce four graphical outputs:</i>
</p>

1.	A histogram of the distribution of QCRSD across the data set.
2.	A kernel density plot of QCRSD vs. D-ratio across the data set.
3.	A PCA scores plot of the data set labelled by sample type.
4.	A bubble scatter plot of molecular mass vs. retention time, with bubble size proportional to QCRSD

*Prior to beginning this tutorial, it is recommended to view the provided static version of the `Jupyter` analysis notebook: [Tutorial 4: Static Notebook](https://cimcb.github.io/MetabSimpleQcViz/Tutorial4.html)*

#### Tutorial 4 steps:
1. Download and unzip the [repository](https://github.com/cimcb/MetabSimpleQcViz) to a folder on your own computer, as in tutorial 3.
2. Create an new notebook:      
    2.1. Ensure “[base (root)]” is selected in the “Applications on” dropdown list of the main panel     
    2.2. Launch Jupyter Notebook   
    2.3. Navigate to the repository root (the “MetabSimpleQcViz” folder)    
    2.4. Click on the “New” button in the top right corner of the page    
    2.5. Select “Python 3” from the list of supported languages (a black Jupyter Notebook called "Untitled" will open)     
    2.6. Rename the notebook by clicking on the text “Untitled” and replacing it with “myQCviz”     
3. Edit the notebook (using the template file as a guide) ...   
4. Save and close the notebook:   
    4.1. Save by clicking on the floppy disk icon (far left on the menu)    
    4.2. Close by clicking “File” and then “Close and Halt”from the top Jupyter menu    
    4.3. The Jupyter session can be closed by clicking on “Quit” on the Jupyter landing page tab of your web browser .   

<br />

<a id="five"></a>
## Tutorial 5: Deploying a Jupyter notebook on Binder via GitHub
1. Create a GitHub account (please follow the instructions on GitHub at https://help.github.com/en/articles/signing-up-for-a-new-github-account) 
2. Create a new repository  
    2.1. Click on the “Repositories” link at the top of the page  
    2.2. Enter “Jupyter_metabQC” into the “Repository name” field 
    2.3. Select the ‘Public’ option for the repository  
    2.3. Select the checkbox to “Initialize this repository with a "README”  
    2.4. Add a license (https://choosealicense.com/)  
    2.5. Click the “Create repository” button 
3. Add files (new Jupyter notebook and the Excel data file ) to the repository  
    3.1. Click on the ‘Upload files’ button    
    3.2. Drag the files (myQCviz.ipynb’ and ‘data.xlsx’) from your computer  
    3.3. Enter the text “Add data and notebook via upload” to the top field under “Commit changes.”       
    3.4. Commit the files to the repository, click on the “Commit changes” button 
4. Build and launch a Binder virtual machine for this repository     
    4.1. Open https://mybinder.org in a modern web browser  
    4.2. Enter the path to the home page of your repository (https://github.com/account_name/Jupyter_metabQC)  
    4.3. Click the ‘Launch’ button 
    4.4. The URL shown in the field “Copy the URL below and share your Binder with others” can be shared with colleagues   

<p align="justify">
Congratulations, you have created your first Binder notebook! Now share it with your colleagues! 
</p>
