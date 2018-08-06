# Best LUT-6 Implementations - 2015
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

### Best results for LUT-6 count

**Arithmetic Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 201  | 73| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Divisor  | 128 |128  |3813  | 1542 | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Hypotenuse | 256 |128  |44635  |4194 | Original Benchmark| /| 
| Log2 | 32 |32 |7344|142 | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Max | 512 |130 |532 |192| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Multiplier | 128 |128 |5681 |120| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Sine | 24 |25 |1347 |62| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Square-root | 128 |64 |3286 |1180| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Square | 64 |128 |3800 |116| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Round-robin arbiter | 256  | 129  | 429  | 24| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Alu control unit  | 7 |26  |29  |2 |Original Benchmark|/|
| Coding-cavlc   | 10 |11  |107  |6 |Original Benchmark|/|
| Decoder | 8 |256  |272  |2 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| i2c controller | 147 |142 |230|7 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| int to float converter | 11 |7 |34 |4 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Memoery controller | 1204 |1231 |2399 |23|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Priority encoder | 128 |8 |118|27|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Lookahead XY router | 60 |30 |53 |6|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Voter | 1001 |1 |1515 |12|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|

### Best results for LUT-6 levels

**Arithmetic Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 419  | 6| L. Amaru |MIG + ABC Mapper|
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Divisor  | 128 |128  |14576 | 238 | L. Amaru |MIG + ABC Mapper|
| Hypotenuse | 256 |128  |149000 |583 | L. Amaru |MIG + ABC Mapper|
| Log2 | 32 |32 |9275|55 | L. Amaru |MIG + ABC Mapper|
| Max | 512 |130 |899|10| L. Amaru |MIG + ABC Mapper|
| Multiplier | 128 |128 |7095 |29| L. Amaru |MIG + ABC Mapper|
| Sine | 24 |25 |1835 |30| L. Amaru |MIG + ABC Mapper|
| Square-root | 128 |64 |11745 |254| L. Amaru |MIG + ABC Mapper|
| Square | 64 |128 |4203 |11| L. Amaru |MIG + ABC Mapper|

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Round-robin arbiter | 256  | 129  | 542  | 6| R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Alu control unit  | 7 |26  |29  |2 |Original Benchmark|/|
| Coding-cavlc   | 10 |11  |120  |4 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Decoder | 8 |256  |272  |2 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| i2c controller | 147 |142 |249|3|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| int to float converter | 11 |7 |44 |3 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Memoery controller | 1204 |1231 |2508 |7|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Priority encoder | 128 |8 |158|4|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Lookahead XY router | 60 |30 |57 |4|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Voter | 1001 |1 |1515 |12|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|

### List of Participants and Methods
| Authors' name | Authors' affiliation | Synthesis method| Description |
| ------------- | ------------- | ------------- | ------------- | 
| Robert K. Brayton & Alan Mishchenko| UC Berkeley | ABC Extreme Mapper | Interactive optimization using a variaty of optimization scripts in [ABC](https://github.com/berkeley-abc/abc)|
| Luca Amaru | EPFL | MIG + ABC Mapper | Based on rewriting algorithms presented in [Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Majority-Inverter Graph: A Novel Data-Structure and Algorithms for Efficient Logic Optimization. DAC 2014: 194:1-194:6](https://infoscience.epfl.ch/record/211244/files/07293649.pdf)|


