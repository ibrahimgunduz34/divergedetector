# Check Diverge!

This script, fetch the last pushed branches from repository and check the each branch for diverge.
If repository has any diverged branch, script send a notification to defined email address or email group in check_diverge.sh file.

# Installation

```shell
$ cd /opt;sudo git clone git@github.com:ibrahimgunduz34/checkdiverge.git; sudo ln -s /opt/checkdiverge/checkdiverge /usr/local/bin/.
```

# Usage
* Enter your git repository
* run the follwing command:
```shell
checkdiverge origin yourmail@yourdomain.com
```

