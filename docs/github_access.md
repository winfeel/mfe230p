# Accessing the Course Private Github

Assignments, assignment solutions, lectures, and other course materials will be maintained and periodically updated on the course's [GitHub](https://github.com) repository. Due to University policy, the repository cannot be shared publically and thus special measures must be taken to grant students access. This document is a brief step-by-step guide on how to obtain access.

### 1. Setup GitHub

First, install git. You can either do so by following [these steps](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) or, if you have `conda` installed, you can simply run

`conda install git`

on [terminal](https://en.wikipedia.org/wiki/Terminal_(macOS)). Next, create a personal [GitHub](https://github.com/) account if you do not have one set up already. You can obtain a free premium account [here](https://education.github.com) using `berkeley.edu` email address.

### 2. Obtain the Access Key

Open [terminal](https://en.wikipedia.org/wiki/Terminal_(macOS)) and execute the following line

`sudo curl "https://s3-us-west-2.amazonaws.com/mfe230p/mfeStudent" -o "$HOME/.ssh/mfeStudent"`

which will download `mfeStudent`, a read-only access key for the mfe230p repository. This key should be stored in your user SSH directory. Next, change the user permissions on the access key by executing

`chmod 400 $HOME/.ssh/mfeStudent`

in terminal.

### 3. Store Git Prefix in Bash Profile

Execute the following code block in terminal to create an alias `mfe230Access` for access key verification when communicating with the repository 

```
printf "\nalias mfe230pAccess=\"GIT_SSH_COMMAND='ssh -i $HOME/.ssh/mfeStudent -F /dev/null'\"" >> $HOME/.bash_profile

source $HOME/.bash_profile
```

To verify, execute `alias mfe230pAccess` which should print something like `alias mfe230pAccess='GIT_SSH_COMMAND='\''ssh -i...` to command line.

### 4. Communicate with the Repository

The repository can be accessed at `git@github.com:mustafaseisa/mfe230p.git` with the passphrase `summer2017`. You should now be able to communicate with the MFE230P repository by using the following general syntax:

```
mfe230pAccess git <arguments>
```

For example, to clone the repository, run

```
mfe230pAccess git clone git@github.com:mustafaseisa/mfe230p.git
```

and enter the passphrase when prompted.