# The EPFL Combinational Benchmark Suite
The EPFL Combinational Benchmark Suite was introduced in 2015 with the aim of defining a new comparative standard for the logic optimization and synthesis community. It originally consisted of 23 combinational circuits designed to challenge modern logic optimization tools. The benchmark suite is divided into arithmetic, random/control and MtM circuits, and each circuit is distributed in Verilog, VHDL, BLIF and AIGER formats.

**Arithmetic Benchmarks**  
The EPFL benchmark suite has 10 arithmetic benchmarks.
They are obtained by an automated mapping of arithmetic computational algorithms into basic logic gates. Examples are square-root, divisor, multipliers, adder, etc; they come in different bit-widths to provide diversity in the implementation complexity. 
The initial implementations are intendedly sub-optimal to test the ability of optimization tools. LUT-6 mapping experiments for the arithmetic EPFL combinational benchmarks are listed in the following Table. They are performed using [ABC]( https://github.com/berkeley-abc/abc) academic tool, with the mapping command *if -K 6*.

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels |
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 254  | 51| 
| Barrel shifter  | 135 |128  |512  |4  |
| Divisor  | 128 |128  |9311  |867 |
| Hypotenuse | 256 |128  |44635  |4194 |
| Log2 | 32 |32 |8008 |77 |
| Max | 512 |130 |842 |56 |
| Multiplier | 128 |128 |5913 |53|
| Sine | 24 |25 |1458 |42|
| Square-root | 128 |64 |5720 |1033|
| Square | 64 |128 |3985 |50|
| **Total** | 1663 |1020 |80638 |6427|

**Random/Control Benchmarks**  
The EPFL benchmark suite has 10 random/control benchmarks. They include various types of controllers, arbiters, routers, converters, decoders, voters and random functions, mapped into simple gates from their behavioral descriptions. Also here, the initial implementations are intendedly unoptimized. 
LUT-6 mapping experiments for the random/control EPFL combinational benchmarks are listed in the following Table. They are performed using [ABC]( https://github.com/berkeley-abc/abc) academic tool, with the mapping command *if -K 6*.

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels |
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| Round-robin arbiter | 256  | 129  | 2722  | 18| 
| Alu control unit  | 7 |26  |29  |2 |
| Coding-cavlc   | 10 |11  |122  |4 |
| Decoder | 8 |256  |287  |2 |
| i2c controller | 147 |142 |365 |4 |
| int to float converter | 11 |7 |49 |3 |
| Memory controller | 1204 |1231 |12096 |25|
| Priority encoder | 128 |8 |210|31|
| Lookahead XY router | 60 |30 |89 |7|
| Voter | 1001 |1 |2691 |16|
| **Total** | 2832 |1841 |18660 |112|

**More than ten Miliong gates (MtM) Benchmarks**  
The EPFL benchmark suite has 3 MtM benchmarks. These benchmarks are designed to challenge the size capacity of modern optimization tools; they are extracted from a set of random Boolean functions, generated with a custom computer program, using as selection metric the implementation complexity. 
LUT-6 mapping experiments for the MtM EPFL combinational benchmarks are listed in the following Table. They are performed using [ABC]( https://github.com/berkeley-abc/abc) academic tool, with the mapping command *if -K 6*.

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels |
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| sixteen | 117  | 50  | 5648909  | 29| 
| twenty  | 137 |60  |7189658 |33 |
| twentythree  | 153 |68  |8246898 |36 |
| **Total** | 407 |178 |21085465|98|

The MtM benchmarks can be downloaded at [https://zenodo.org/record/2572934#.XGxRiS3MzuM](https://zenodo.org/record/2572934#.XGxRiS3MzuM)

## Best LUT-6 implementation 
We keep track of the best optimization results, mapped into LUT-6, for size and depth metrics. 

#### Submit your best LUT-6 implementation!
We encourage researchers to submit their best LUT-6 implementations in BLIF format for one or more of the benchmarks:
- at *benchmarks@groupes.epfl.ch* (in case the files exceed 3 MB please provide a download link in the email) 
- or with a [pull request](https://help.github.com/articles/creating-a-pull-request/) to this repository. 

Also the methodology used to optimize/map the circuits needs to be specified. We will run combinational equivalence checking and verify the claimed improvements over the current best implementation. If passing all tests, we will publish online the circuit together with the author’s name and affiliation as symbolic recognition.  

**The results presented above are NOT the best results, but they are the ORIGINAL benchmarks. All best known results can be found at the [tags on this repository](https://github.com/lsils/benchmarks/releases).**

## References 
The EPFL combinational benchmarks are explained in the paper [The EPFL Combinational Benchmark Suite](https://infoscience.epfl.ch/record/207551/files/IWLS15.pdf), presented at the [International Workshop on Logic Synthesis 2015](http://www.iwls.org/iwls2015/)
