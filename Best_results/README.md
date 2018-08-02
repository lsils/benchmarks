# Best LUT-6 Implementations - 2015
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

###Best results for LUT-6 count

**Arithmetic Benchmarks**
| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 201  | 73| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Barrel shifter  | 135 |128  | 512  |4  | Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Divisor  | 128 |128  |3813  | 1542 | Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Hypotenuse | 256 |128  |44635 |4194 | Original Benchmark| /|
| Log2 | 32 |32 |7344|142 | Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Max | 512 |130 |532 |192| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Multiplier | 128 |128 |5681 |120| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Sine | 24 |25 |1347 |62| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Square-root | 128 |64 |3286 |1180| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|
| Square | 64 |128 |3800 |116| Robert K. Brayton & Alan Mishchenko|ABC Extreme Mapper|


### List of Participants and Methods
| Authors' name | Authors' affiliation | Synthesis method| Description |
| ------------- | ------------- | ------------- | ------------- | 
Robert K. Brayton & Alan Mishchenko| UC Berkeley | ABC Extreme Mapper | Interactive optimization using a variaty of optimization scripts in [ABC](https://github.com/berkeley-abc/abc)|
Luca Amaru | EPFL | MIG + ABC Mapper | Based on rewriting algorithms presented in [Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Majority-Inverter Graph: A Novel Data-Structure and Algorithms for Efficient Logic Optimization. DAC 2014: 194:1-194:6](https://infoscience.epfl.ch/record/211244/files/07293649.pdf)


