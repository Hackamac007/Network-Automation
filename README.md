# Course background information
This file contains background information about the course, including
configuration files and versions.


## Development machine
I used an Amazon Linux platform on EC2 for this course, but any Linux
device will do. I'd also suggest setting up a Python virtual
environment (`venv`) to ensure there are no collisions with Python
packages between this course and the system Python instance.


## Network details
I used Cisco CSR1000v and Cisco XRv9000 in this network. Software versions are shown below.

Configurations for R1, R2, and R3 are included in the `configs/` directory.
You may load these up ahead of time, and given the usage of GRE tunnels to
interconnect one another, they should work in most public cloud environments.

## Python details
I used Python 3.7.3 for this.

```
$ python --version
Python 3.7.3
```

I've also included a `requirements.txt` which you can use to get started
quickly using `pip install -r requirements.txt`
