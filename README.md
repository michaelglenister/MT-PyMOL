<img src="https://travis-ci.org/nizamibilal/pyMODE-TASK.svg?branch=master" align="right"> <img src='https://readthedocs.org/projects/pymode-task/badge/?version=latest' align="right" />

# MT-PyMOL
MODE-TASK plugin for PyMOL

## Installation

*Requirements:*
```
python
Tkinter
Pmw
numpy==1.13.1
cython==0.26
scikit-learn==0.19.0
scipy==0.19.1
sklearn==0.0
matplotlib==2.0.2
mdtraj==1.8.0
```

*Download the project:*
```bash
git clone https://github.com/RUBi-ZA/pyMODE-TASK.git
```

OR

Download zip from github page and extract to a directory.

*Install dependencies:*

run the following command from within pyMODE-TASK
```
sudo pip install -r requirements.txt
```

pyMODE-TASK requires Tkinter and Pmw.1.3. Tkinter comes prepackaged with most standard python. Pmw could be installed by following the instruction from:

http://pmw.sourceforge.net/doc/starting.html

*Install plugin in pymol:*
1. Start pymol
2. Go to Plugin --> Plugin Manager and clcik on install new plugin tab. Under install from local file click on choose file.. button.
Browse the pyMODE-TASK.py and follow the on screen installation instructions. 
3. If everything is goes well, you can start the plugin from pymol plugin menu. 

## Usage

For more detailed documentation on installation and usage of the tool suite please see our [ReadTheDocs](http://pymode-task.readthedocs.io/en/latest/index.html) site

### TODO list:
- [X] Fully functional and ready to install plugin.
- [X] Resize/adjust NMA tab.
- [ ] Add progress bar.
- [ ] Update link in MODE-TASK documentation.
- [ ] Add better handling of exceptions in NMA tab.
- [ ] Add feature to identify the MD frame in the PCA projection plot. 


