# qap benchmark
The instances used for the benchmark come from the [QAPLIB](https://coral.ise.lehigh.edu/data-sets/qaplib/qaplib-problem-instances-and-solutions/).We used almost all datasets, including a total of 124 instances.

We found best solutions of 68 instances, each in 10s. for The instances which not found best solutions, we set the max search time limit to 60s, and then found best solutions for another 13 instances.  

x:instance, y:gap(%)  

max search time limit is 10s
<img src="https://github.com/DubingXiang/light_or-docs/raw/master/benchmarks/qap/gaps_10s.svg"/>
max search time limit is 60s
<img src="https://github.com/DubingXiang/light_or-docs/raw/master/benchmarks/qap/gaps_60s.svg"/>