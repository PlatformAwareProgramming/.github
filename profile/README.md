# Platform-aware programming

It is the practice of writing *computationally demanding code* making assumptions about *features* specific to the resources of the target execution platform, such as deep memory hierarchies, multiprocessor nodes of a cluster, cluster's interconnection/network, processors of a multiprocessor system, cores of a multicore processor, accelerators (GPUs, FPGAs, MICs, etc), and so on.

It is a common practice among developers of applications whose viability depends on taking full advantage of the performance of high-throughput and high-performance computing (HTC/HPC) systems. Traditionally, they are programmers of particular niches, such as scientific computing, especially when interested in using [high-end parallel computing architectures](https://www.top500.org/).

The practice of platform-aware programming tends to spread as heterogeneous computing architectures, such as accelerators, are becoming essential tools to enable many Artificial Intelligence (AI) and Data Analytics applications. In addition, the growing interest in using accelerator technology (GPUs, FPGAs, etc) has driven the heterogeneity of both vendors and products available on the market. In fact, heterogeneous computing is becoming even more heterogeneous over the years. 

Despite the efforts of academia and industry to propose new common interfaces and abstractions for programming various kinds of accelerators, there are many situations where programmers are forced to use specific accelerator features to achieve their maximum performance. In fact, the most efficient use of heterogeneous computing still requires heterogeneous programming. However, the efforts of programming language designers and researchers are scarce on the development of heterogeneous programming abstractions based on respect for the heterogeneous nature of the execution environments. They are mainly focused on dealing with performance portability issues behind general interfaces and abstractions.

This organization is dedicated to hosting projects that offer programming interfaces and abstractions to help programmers deal with the complexity of platform-aware programming, especially seeking to explore the capabilities of different accelerator architectures, as well as specific features of processors and clusters interconnections. 

Our first initiative is [PlatformAware.jl](https://github.com/PlatformAwareProgramming/PlatformAware.jl), a package that aims to enable platform-aware programming in tie [Julia](https://juliagpu.org/) programming language. It is hosted in this organization.
