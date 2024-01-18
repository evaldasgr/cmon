# cmon
cmon is a simple utility for monitoring per-core CPU, RAM and GPU utilization on Linux systems.

# Usage
To see immediate utilization, start the utility without any arguments:
```sh
$ cmon
[CPU]
CPU0 usage:	1%
CPU1 usage:	0%
CPU2 usage:	0%
CPU3 usage:	22%
CPU4 usage:	0%
CPU5 usage:	0%
CPU6 usage:	0%
CPU7 usage:	0%
CPU8 usage:	0%
CPU9 usage:	79%
CPU10 usage:	1%
CPU11 usage:	0%

[Memory]
RAM usage:	3599/15909 MiB
SWAP usage:	0/8192 MiB

[GPU]
GPU usage:	0%
VRAM usage:	731/8192 MiB
```

To actively monitor utilization, start the utility with the watch command:
```sh
$ watch -n1 cmon
```
