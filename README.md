# MemoryStorage_Filesystem
Yongseob <tel.05056622231@gmail.com>

# Introduction
This file system is purposed to evaluate the write intensive workload in the NUMA(Non-Uniform Memory Access) system.

# How to use
Requirement : This file system needs patched Linux Kernel (MemoryStorage_Kernel)

## Building filesystem

~~~
$ make
~~~

## Running this filesystem

~~~
$ sudo insmod r2nvmm.ko
# mount -t r2nvmm -o r2nvmm_test /mnt/r2nvmm
~~~


# Acknowledgement
This work was supported by Institute for Information & communicationsTechnology Promotion(IITP) grant funded by the Korea government(MSIT)(No.B0101-17-0644,Research on  High Performance and Scalable Manycore Operating System)
