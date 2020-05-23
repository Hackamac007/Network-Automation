# Network-Automation

# Course background information
This file contains background information about the course, including
configuration files and versions.

Please contact me on Twitter `@nickrusso42518` or in the course
discussion with any questions you have.

## Development machine
I used an Amazon Linux platform on EC2 for this course, but any Linux
device will do. I'd also suggest setting up a Python virtual
environment (`venv`) to ensure there are no collisions with Python
packages between this course and the system Python instance.

The following packages are not required but may be useful to you. You
may install them using your OS package manager, such as `yum` or `apt`.
Some of these may come as default options in your distribution are they
are all common.

```
vim-enhanced
tree
make
git
```

## Network details
I used Cisco CSR1000v and Cisco XRv9000 in this network, as explained in
the Globomantics background. Software versions are shown below.

```
CSR1000v - Cisco IOS XE Software, Version 16.09.02
XRv9000 - Cisco IOS XR Software, Version 6.3.1
```

Configurations for R1, R2, and R3 are included in the `configs/` directory.
You may load these up ahead of time, and given the usage of GRE tunnels to
interconnect one another, they should work in most public cloud environments.

## Python details
I used Python 3.7.3 for this course. Python 3.6 is the absolute minimum,
and in that case, you won't be able to use `breakpoint()` to invoke `pdb`.
This is explained in the course video content. You can install the newest
Python version here: `https://www.python.org/downloads/`

```
$ python --version
Python 3.7.3
```

Below is the full list of Python packages in my `venv` with their versions.
I've also included a `requirements.txt` which you can use to get started
quickly using `pip install -r requirements.txt`
