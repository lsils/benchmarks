# Best LUT-6 Implementations - 2016
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

### Best results for LUT-6 count

**Arithmetic Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 192 | 64| Winston Haaswijk  |MIG LUT Mapper |
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| **Divisor**  | **128** |**128**  |**3268**  | **1208** | **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Hypotenuse** | **256** |**128**  |**40406**  |**4532** | **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Log2** | **32** |**32** |**6574**|**119** | **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Max** | **512** |**130** |**523** |**189**| **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Multiplier** | **128** |**128** |**4923** |**90**|  **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Sine** | **24** |**25** |**1229** |**55**| **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Square-root** | **128** |**64** |**3077** |**1106**| **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Square** | **64** |**128** |**3246** |**74**|  **Gai Liu & Zhiru Zhang**| **PIMap**|

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| **Round-robin arbiter** | **256**  | **129**  | **409**  | **23**| **Gai Liu & Zhiru Zhang**| **PIMap**|
| **Alu control unit**  | **7** |**26**  |**27**  |**2** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Coding-cavlc**   | **10** |**11**  |**101**  |**6** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Decoder** |**8** |**256**  |**270**  |**2** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **I2c controller** | **147** |**142** |**227**|**7** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Int to float converter** | **11** |**7** |**28** |**6** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Memory controller** | **1204** |**1231** |**2354** |**22**|**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Priority encoder** | **128** |**8** |**110**|**26**|**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Lookahead XY router** | **60** |**30** |**52** |**6**|**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Voter** | **1001** |**1** |**1301** |**17**|**Gai Liu & Zhiru Zhang**| **PIMap**|

**MtM Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Sixteen | 117	|50|	5648909	|29| Original Benchmark| /|
| Twenty  | 137|60|	7189658|	33 |Original Benchmark|/|
| Twentythree  |153|	68 | 4936053 | 23 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|


### Best results for LUT-6 levels

**Arithmetic Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 511  | 5| A. Mishchenko |ABC Ultimate Mapper |
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Divisor  | 128 |128  |47964 | 230 | A. Mishchenko |ABC Ultimate Mapper |
| Hypotenuse | 256 |128  | 146302 |573 | A. Mishchenko |ABC Ultimate Mapper |
| **Log2** | **32** |**32** |**9218**|**55** |   **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Max** | **512** |**130** |**882**|**10**|   **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| Multiplier | 128 |128 |8215 |28| A. Mishchenko |ABC Ultimate Mapper |
| **Sine** | **24** |**25** |**1801** |**30**|   **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Square-root** | **128** |**64** |**11680** |**254**|   **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Square** | **64** |**128** |**4038** |**11**|   **Alan Mishchenko et al. **| **SAT LUT Mapper**|

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Round-robin arbiter | 256 | 129  | 2884  | 5| A. Mishchenko |ABC Ultimate Mapper |
| **Alu control unit**  | **7** |**26**  |**27**  |**2** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **Coding-cavlc**   | **10** |**11**  |**115**  |**4** | **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Decoder** |**8** |**256**  |**270**  |**2** |**Gai Liu & Zhiru Zhang**| **PIMap**|
| **I2c controller** | **147** |**142** |**244**|**3**| **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Int to float converter** | **11** |**7** |**41** |**3** | **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Memory controller** | **1204** |**1231** |**2490** |**7**| **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| **Priority encoder** | **128** |**8** |**157**|**4**| **Alan Mishchenko et al. **| **SAT LUT Mapper**|
| Lookahead XY router | 60 |30 |57 |4|R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| **Voter** | **1001** |**1** |**1469** |**12**| **Alan Mishchenko et al. **| **SAT LUT Mapper**|

**MtM Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Sixteen | 117	|50|	5648909	|29| Original Benchmark| /|
| Twenty  | 137|60|	7189658|	33 |Original Benchmark|/|
| Twentythree  |153|	68 | 4936053 | 23 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|

### List of Participants and Methods
| Authors' name | Authors' affiliation | Synthesis method| Description |
| ------------- | ------------- | ------------- | ------------- | 
| Robert K. Brayton & Alan Mishchenko| UC Berkeley | ABC Extreme Mapper | Interactive optimization using a variaty of optimization scripts in [ABC](https://github.com/berkeley-abc/abc)|
| Luca Amaru | EPFL | MIG + ABC Mapper | Based on rewriting algorithms presented in [Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Majority-Inverter Graph: A Novel Data-Structure and Algorithms for Efficient Logic Optimization. DAC 2014: 194:1-194:6](https://infoscience.epfl.ch/record/211244/files/07293649.pdf)|
| Alan Mishchenko| UC Berkeley | ABC Ultimate Mapper | Based on lazy man synthesis using recorded [database](http://people.eecs.berkeley.edu/~alanmi/temp5/rec6Lib_final_filtered3_recanon.aig). ABC script: "rec_start rec6Lib_final_filtered3_recann.aig; read file.aig; resyn2; resyn2; if -y -K 6; if -y -K 6;" // repeat until no further improvement|
| Winston Haaswijk et al. | EPFL | MIG LUT Mapping | Based on resynthesis algorithms presented in Winston Haaswijk, Mathias Soeken, Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: LUT Mapping and Optimization for majority-inverter graphs. IWLS 2016 |
| Gai Liu & Zhiru Zhang | Cornell University | PIMap | Based on parallelized iterative improvement mapping presented in [Gai Liu and Zhiru Zhang: A parallelized iterative improvement approach to area optimization for LUT-based technology mapping. FPGA, 2017](http://delivery.acm.org/10.1145/3030000/3021735/p147-liu.pdf?ip=198.182.47.47&id=3021735&acc=CHORUS&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1535664503_83b042899a419486179f19e4dbd2e1ca) |
| Alan Mishchenko et al. | UC Berkeley | SAT LUT Mapper | Based on SAT based remapping algorithm. ABC script (the file.blif is best known results from 2015): "read file.blif; &satlut -N 64 -C 10000"|



