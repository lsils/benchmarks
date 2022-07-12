# Best LUT-6 Implementations - 2022
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

### Best results for LUT-6 count

**Arithmetic Benchmarks** 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels   | Authors                       | Method             |
| ------------- | ------------- | ------------- |-------------|----------|-------------------------------|--------------------| 
| **Adder** | **256**  | **129**  | **134**     | **121**  | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
| Barrel shifter  | 135 |128  | 512         | 4        | R. K. Brayton & A. Mishchenko | ABC Extreme Mapper |
| **Divisor**  | **128** | **128**   | **3104**    | **1095** | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Hypotenuse**  |  **256**  | **128**   | **39556**   | **4550** | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Log2**  |  **32**  | **32**  | **6447**    | **137**  | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Max**  |  **512**  | **130**  | **512**     | **193**  | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Multiplier**  |  **128**  | **128**  | **4485**    | **109**  | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Sine**  |  **24**  | **25**  | **1200**    | **60**   | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**     |
|  **Square-root**  |  **128**  | **64**  | **2996**    | **1119** | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**          |
|  Square  | 64  | 128  | 3232        | 76       | L. Amaru et al.               | LUT-optimization   |

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method                |
| ------------- | ------------- | ------------- |-------------|--------| ------------- |-----------------------| 
|  **Round-robin arbiter**  |  **256**   |  **129**   | **299**     | **80** | **A. Grosnit, C. Feng, X. Li, et al.**         | **NAILS**        |
|  **Alu control unit**   |  **7**  | **26**   | **26**      | **2**  | **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS**        |
|  Coding-cavlc    |  10  | 11   | 68          | 3      | L. Machado and J. Cortadella | Support-Reducing Decomp |
|  Decoder  | 8  | 256   | 264         | 2      | L. Machado and J. Cortadella | Support-Reducing Decomp |
|  I2c controller  |  147  | 142  | 200         | 10     | L. Machado and J. Cortadella | Support-Reducing Decomp |
|  Int to float converter |  11  | 7  | 24          | 4      | I. Lemberski, A. Suponenkovs | Resubstitution        |
|  **Memory controller**  |  **1204**  | **1231**  | **2012**    | **21**     | **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS**        |
|  Priority encoder  |  128  | 8  | 100         | 26     | A. Grosnit, C. Feng, X. Li, et al. | NAILS                 |
|  Lookahead XY router | 60 |30 | 50          | 5      |L. Machado and J. Cortadella| Support-Reducing Decomp |
|  **Voter** | **1001** | **1** | **1254**    | **15** | **A. Grosnit, C. Feng, X. Li, et al.** | **NAILS**        |

**MtM Benchmarks** 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Sixteen | 117	|50|	5648909	|29| Original Benchmark| /|
| Twenty  | 137|60|	7189658|	33 |Original Benchmark|/|
| Twentythree  |153|	68 | 4936053 | 23 |R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|


### Best results for LUT-6 levels

**Arithmetic Benchmarks** 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels  | Authors | Method |
| ------------- | ------------- | ------------- |------------|---------| ------------- | ------------- | 
| **Adder** | **256**  | **129**  | **378**    | **5**   |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
| Barrel shifter  | 135 |128  | 512        | 4       | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| **Divisor**  | **128** | **128**  | **24426**  | **179** |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
| **Hypotenuse** | **256** | **128**  | **177887** | **493** |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
|  **Log2**  | **32**  | **32**  | **8781**   | **52**  |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
|  **Max** |  **512**  | **130**  | **1569**   | **7**   |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
| **Multiplier** | **128** | **128** | **12996**  | **25**  |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
|  **Sine**  |  **24**  | **25**  | **681808**     | **10**      |  **A. Grosnit, C. Feng, X. Li, et al.**   | **NAILS** |
|  **Square-root**  |  **128**  | **64**  | **42207**  | **173** | **A. Grosnit, C. Feng, X. Li, et al.** | **NAILS** |
|  **Square**  |  **64**  | **128**  | **3947**   | **10**  | **A. Grosnit, C. Feng, X. Li, et al.** | **NAILS** |

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors                      | Method |
| ------------- | ------------- | ------------- |-------------| ------------- |------------------------------| ------------- | 
|  **Round-robin arbiter** | **256** | **129**  | **1036**    | **5** | **A. Grosnit, C. Feng, X. Li, et al.**        | **NAILS** |
|  **Alu control unit**   |  **7**  | **26**   | **26**      | **2**  | **A. Grosnit, C. Feng, X. Li, et al.**        | **NAILS** |
|  Coding-cavlc    |  10  | 11   | 68          | 3 | L. Machado and J. Cortadella |  Support-Reducing Decomp |
|  Decoder  | 8  | 256   | 264         | 2  | L. Machado and J. Cortadella | Support-Reducing Decomp |
|  **I2c controller**  |  **147**  | **142**  | **221**     | **3** | **L. Fan & C. Wu**           | **scaleSyn mapper** |
|  Int to float converter  |  11  | 7  | 27          | 3  | L. Machado and J. Cortadella |  Support-Reducing Decomp |
|  **Memory controller**  |  **1204**  | **1231**  | **2203**    | **6** |  **A. Grosnit, C. Feng, X. Li, et al.**        | **NAILS** |
|  **Priority encoder**  | **128** | **8**  | **132**     | **4** | **A. Grosnit, C. Feng, X. Li, et al.**           | **NAILS** |
|  Lookahead XY router | 60 | 30 | 56          | 3 | S. Jang and A. Mishchenko    | iMap |
|  **Voter**  |  **1001**  | **1**  | **1447**    | **11** | **A. Grosnit, C. Feng, X. Li, et al.**        | **NAILS** |

**MtM Benchmarks** 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels  | Authors | Method |
| ------------- | ------------- | ------------- | ------------ |---------| ------------- | ------------- | 
| **Sixteen** | **117**	|**50**|	**3809921**	| **16**  | **A. Grosnit, C. Feng, X. Li, et al.**    | **NAILS** |
| **Twenty**  | **137**|**60**|	**4735466**| 	**15** | **A. Grosnit, C. Feng, X. Li, et al.**    | **NAILS** |
| **Twentythree**  |**153**|	**68** | **5735450** | **16**  | **A. Grosnit, C. Feng, X. Li, et al.**    | **NAILS** |

### List of Participants and Methods
| Authors' name                       | Authors' affiliation | Synthesis method        | Description                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------------------| ------------- |-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| Robert K. Brayton & Alan Mishchenko | UC Berkeley | ABC Extreme Mapper      | Interactive optimization using a variaty of optimization scripts in [ABC](https://github.com/berkeley-abc/abc)                                                                                                                                                                                                                                                                                                                                     |
| Luca Amaru                          | EPFL | MIG + ABC Mapper        | Based on rewriting algorithms presented in [Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Majority-Inverter Graph: A Novel Data-Structure and Algorithms for Efficient Logic Optimization. DAC 2014: 194:1-194:6](https://infoscience.epfl.ch/record/211244/files/07293649.pdf)                                                                                                                                             |
| Alan Mishchenko                     | UC Berkeley | ABC Ultimate Mapper     | Based on lazy man synthesis using recorded [database](http://people.eecs.berkeley.edu/~alanmi/temp5/rec6Lib_final_filtered3_recanon.aig). ABC script: "rec_start rec6Lib_final_filtered3_recann.aig; read file.aig; resyn2; resyn2; if -y -K 6; if -y -K 6;" // repeat until no further improvement                                                                                                                                                |
| Winston Haaswijk et al.             | EPFL | MIG LUT Mapping         | Based on resynthesis algorithms presented in Winston Haaswijk, Mathias Soeken, Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: LUT Mapping and Optimization for majority-inverter graphs. IWLS 2016                                                                                                                                                                                                                           |
| Gai Liu & Zhiru Zhang               | Cornell University | PIMap                   | Based on parallelized iterative improvement mapping presented in [Gai Liu and Zhiru Zhang: A parallelized iterative improvement approach to area optimization for LUT-based technology mapping. FPGA, 2017](http://delivery.acm.org/10.1145/3030000/3021735/p147-liu.pdf?ip=198.182.47.47&id=3021735&acc=CHORUS&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1535664503_83b042899a419486179f19e4dbd2e1ca) |
| Alan Mishchenko et al.              | UC Berkeley | SAT LUT Mapper          | Based on SAT based remapping algorithm. ABC script (the file.blif is best known results from 2015): "read file.blif; &satlut -N 64 -C 10000"                                                                                                                                                                                                                                                                                                       |
| Luca Amaru et al.                   | Synopsys Inc. | Exact Delay synthesis   | Based on rewriting using exact delay database as presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Pierre-Emmanuel Gaillardon, Janet Olson, Rober Brayton, Giovanni De Micheli: Enabling Exact Delay Synthesis. ICCAD, 2017](https://people.eecs.berkeley.edu/~alanmi/publications/2017/iccad17_eds.pdf)                                                                                              |
| L. Machado and J. Cortadella        | Universitat Politècnica de Catalunya | Support-Reducing Decomp | Based on the algorithm presented in [Lucas Machado and Jordi Cortadella: Support-Reducing Functional Decomposition for FPGA Technology Mapping. IWLS, 2018](http://www.cs.upc.edu/~jordicf/gavina/BIB/files/iwls2018_FPGA.pdf) and in [Lucas Machado and Jordi Cortadella: Support-Reducing Decomposition for FPGA Mapping. TCAD, 2018](https://ieeexplore.ieee.org/document/8509141)                                                              |
| L. Amaru et al.                     | Synopsys Inc. | Boolean Resynthesis     | Boolean resynthesis techniques. Algorithm presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Janet Olson, Robert K. Brayton, Giovanni De Micheli: Improvements to Boolean resynthesis. DATE, 2018](https://people.eecs.berkeley.edu/~alanmi/publications/2018/date18_resyn.pdf)                                                                                                                        |
| E. Testa et al.                     | EPFL and Synopsys Inc. | Boolean Methods         | Algorithm presented in [Eleonora Testa, Luca Gaetano Amarù, Mathias Soeken, Alan Mishchenko, Patrick Vuillod, Jiong Luo, Christopher Casares, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Scalable Boolean Methods In A Modern Synthesis Flow. DATE, 2019](https://msoeken.github.io/papers/2019_date_2.pdf)                                                                                                                                  |
| I. Lemberski et al.                 | Ventspils University for Applied Sciences | Resubstitution          | Based on the resubstitution method presented in [Igor Lemberski, Artjoms Suponenkovs, Marina Uhanova: LUT-Oriented Asynchronous Logic Design Based on Resubstitution. DTIS, 2019](https://ieeexplore.ieee.org/document/8734973)                                                                                                                                                                                                                    |
| L. Amaru et al.                     | Synopsys Inc. | LUT-optimization        | Based on LUT optimization presented in [Luca Amarú, Vinicius Possani, Eleonora Testa, Felipe Marranghello, Christopher Casares, Jiong Luo, Patrick Vuillod, Alan Mishchenko, Giovanni De Micheli: LUT-Based Optimization For ASIC Design Flow. DAC, 2021](https://ieeexplore.ieee.org/document/9586132)                                                                                                                                            |
| S. Jang and A. Mishchenko           | UC Berkeley | iMap                    | A portfolio logic synthesis system based on [ABC](https://github.com/berkeley-abc/abc)                                                                                                                                                                                                                                                                                                                                                             |
| Longfei Fan and Chang Wu            | Fudan University | scaleSyn mapper         | Area-oriented technology mapping combined with pre- and post-mapping logic optimization methods in ABC                                                                                                                                                                                                                                                                                                                                             |
| Alessandro Tempia Calvino           | EPFL | XAG optimization        | Based on XAG optimization and post-mapping methods in ABC                                                                                                                                                                                                                                                                                                                                                                                          |
| A. Grosnit, C. Feng, X. Li, et al.  | Huawei Noah's Ark Lab | NAILS                   | A collection of heuristic aided Bayesian Optimization and heuristic methods from AI4EDA team of  Noah's Ark Lab.<br/>Contributors: Antoine Grosnit, Chang Feng, Xing Li, Rasul Tutunov, Junjie Ye, Chao Wang, Lei Chen, Mingxuan Yuan, Jia Zeng, Weihua Sheng, Cedric Malherbe, Xingchen Wan, Binxin Ru, Haitham Bou-Ammar, Jun Wang, Jianye Hao.                                                                                                  |                                                                                                                                                                                                                                                                                                                                   |
