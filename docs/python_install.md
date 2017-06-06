# Setting up Python

We will install and manage [Python 3](https://www.python.org) via [Minconda](https://conda.io/miniconda.html), a lightweight version of the famous [Anaconda](https://www.continuum.io/downloads) package manager. The following tutorial assumes you are operating on a Macintosh computer.

### 1. Install Miniconda

First, open Terminal and execute the following codeblock to download and install Miniconda

```
cd $HOME/Downloads
curl "https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh" -o "miniconda3.sh"

bash miniconda3.sh -b
printf '\n# added by Miniconda3 Installer \nexport PATH="$HOME/miniconda3/bin:$PATH"' >> $HOME/.bash_profile
rm -f miniconda.sh

source $HOME/.bash_profile
```

The `-b` flag will silently install Miniconda in batch mode.

### 2. Install Python Packages

Executing the following codeblock will install a set of useful Python packages needed for completing the assignments and for scientific computing in general.

```
conda install -c cvxgrp cvxpy numpy scipy pandas matplotlib jupyter git -y
conda update --all -y
conda clean --all -y
```

### 3. Verify Installation

Execute the following line

```
echo "import cvxpy, numpy, scipy, pandas, matplotlib, jupyter" | ipython
```

If no errors are returned, then installation was successful.