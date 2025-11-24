# StatMiner
> Under development

## Description:
A Python-based geochemistry data analysis toolkit designed to perform statistical analyses, visualisation, and exploratory data mining on geochemical datasets.

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/rahulrox9/StatMiner.git
cd StatMiner
```

### 2A. Using Conda
#### Create and activate a dedicated environment:
``` conda
conda create -n statminer_env python=3.11
conda activate statminer_env
```
#### Make sure `pip` is available:
``` conda
python -m ensurepip --upgrade
```
#### Now install dependencies:
``` conda
pip install -r requirements.txt
```

### 2B. Using standard Python (venv)
#### Create a virtual environment and activate it:
``` python
python -m venv statminer_env
```
#### Activate the environment:
Windows
```
statminer_env\Scripts\activate
```
Linux/macOS
```
source statminer_env/bin/activate
```
#### Then ensure `pip` is up to date and install dependencies: 
```bash
python -m ensurepip --upgrade
pip install --upgrade pip
pip install -r requirements.txt
```

## Files
 - README.md          : Project documentation
 - requirements.txt   : Python dependencies
 - run_StatMiner.py   : Python file to be executed
 - User_config.py     : User input file
 - Stat_functions.py  : Python file with all the statistical functions used
%
% ## Usage
% 1. Place your geochemical datasets in the data folder.
% 2. Run analysis scripts:
% python your_code_files.py
% 3. Examine generated plots and results.
%
% ## Dependencies
% - pandas
% - numpy
% - matplotlib
% - seaborn
% - scipy
% - pingouin
%
% ## Licence
% [Specify your licence here, e.g., MIT Licence]
%
% ## Author
% Your Name
% Contact: your.email@example.com


 2. Navigate to the project folder:
%      cd StatMiner
%   3. Create a virtual environment (recommended):
%      python -m venv env
%      source env/Scripts/activate   # Windows
%      source env/bin/activate       # Linux/macOS
%   4. Install dependencies:
%      pip install -r requirements.txt
%
% Files:
%   - README.md             : Project documentation
%   - requirements.txt      : Python dependencies
%   - your_code_files.py    : Core analysis scripts
%
% Usage:
%   1. Place your geochemical datasets in the data folder.
%   2. Run analysis scripts:
%      python your_code_files.py
%   3. Examine generated plots and results.
%
% Dependencies:
%   - pandas
%   - numpy
%   - matplotlib
%   - seaborn
%   - scipy
%   - pingouin
%
% Licence:
%   [Specify your licence here, e.g., MIT Licence]
%
% Author:
%   Your Name
%   Contact: your.email@example.com
