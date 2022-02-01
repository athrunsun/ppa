# My PPA (Personal Package Archives) repository for Ubuntu derived Linux distros [![Build Status](https://dev.azure.com/okampfer/ppa_build/_apis/build/status/ppa_build?branchName=master)](https://dev.azure.com/okampfer/ppa_build/_build/latest?definitionId=5&branchName=master)

Included packages:

- [sublime-text](https://www.sublimetext.com)
- [sublime-merge](https://www.sublimemerge.com)

## Usage
```shell
curl -s --compressed https://athrunsun.github.io/ppa/ubuntu/KEY.gpg | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/athrun-ppa.list https://athrunsun.github.io/ppa/ubuntu/athrun_ppa.list
sudo apt update

# Install sublime-text
sudo apt install sublime-text

# Install sublime-merge
sudo apt install sublime-merge
```

## Reference
- [Hosting your own PPA repository on GitHub](https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html)
- [assafmo/ppa](https://github.com/assafmo/ppa)
