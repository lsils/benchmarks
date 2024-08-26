# Best LUT-6 Implementations - 2023
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

### Best results for LUT-6 count

Arithmetic Benchmarks 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 129 | 126 | T. Besson | ABC-DE: ABC Design Explorer |
| Barrel shifter  | 135 | 128  | 512  | 4  | R. K. Brayton & A. Mishchenko| ABC Extreme Mapper|
| **Divisor**  | **128** | **128**   | **3085**   |  **1100**  | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Hypotenuse**  |  **256**  | **128**   | **36507**   | **4631**  | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Log2**  | **32**  | **32**  | **6012** | **257**  | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Max**  |  **512**  | **130**  | **511**  | **134** | **H. Wang and P. Wang** | **EasyLS**  |
|  **Multiplier**  |  **128**  | **128**  | **4314**  | **208** | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Sine**  |  **24**  | **25**  | **1023**  | **110** | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Square-root**  |  **128**  | **64**  | **2966**  | **1185** | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Square**  | **64**  | **128**  | **2935**  | **200** | **A. Costamagna et al.** | **Information graph-based resubstitution** |

Random-Control Benchmarks

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|  **Round-robin arbiter**  |  **256**   |  **129**   |  **261**   |  **93** | **T. Besson** | **ABC-DE: ABC Design Explorer** |
|  Alu control unit   |  7  | 26   | 25 | 2  | A. Grosnit, C. Feng, X. Li, et al. | NAILS |
|  **Coding-cavlc**    | **10**  | **11**   | **49**   | **7**  | **F. Reichl, F. Slivovsky, S. Szeider** | **Exact Subcircuit Synthesis** |
|  Decoder  | 8  | 256   | 264   | 2  | L. Machado and J. Cortadella |  Support-Reducing Decomp |
|  **I2c controller**  |  **147**  | **142**  | **175** | **7**  | **H. Wang and P. Wang** | **EasyLS** |
|  **Int to float converter** |  **11**  | **7**  | **18**  | **5**  | **F. Reichl, F. Slivovsky, S. Szeider** | **Exact Subcircuit Synthesis** |
|  **Memory controller**  |  **1204**  | **1231**  | **1694**  | **14** | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Priority encoder**  |  **128**  | **8**  | **92** | **30** | **A. Costamagna et al.** | **Information graph-based resubstitution** |
|  **Lookahead XY router** | **60** | **30** | **18** | **9** | **F. Reichl, F. Slivovsky, S. Szeider** | **Exact Subcircuit Synthesis** |
|  **Voter** | **1001** | **1** | **1166** | **34**  | **F. Reichl, F. Slivovsky, S. Szeider** | **Exact Subcircuit Synthesis** |

MtM Benchmarks 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Sixteen | 117	| 50 |	3282958	| 23 |  T. Besson | ABC-DE: ABC Design Explorer |
| Twenty  | 137 | 60 |	4166467 | 24 |  T. Besson | ABC-DE: ABC Design Explorer |
| Twentythree  | 153 | 68 | 470892 | 25 |  T. Besson | ABC-DE: ABC Design Explorer |


### Best results for LUT-6 levels

Arithmetic Benchmarks 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 347  | 5 | J. Yuan, J. Ye, et al. | EasyRL |
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| **Divisor**  | **128** | **128**  | **22258** | **173** | **H. Wang and P. Wang** | **EasyLS** |
| **Hypotenuse** | **256** | **128**  | **152793** | **473** | **A. Tempia Calvino et al.** | **LUT mapping with Boolean decomposition** |
|  **Log2**  | **32**  | **32**  | **9613** | **51**  |  **A. Tempia Calvino et al.** | **LUT mapping with Boolean decomposition** |
|  **Max** |  **512**  | **130**  | **1110** | **6** | **H. Wang and P. Wang** | **EasyLS** |
| **Multiplier** | **128** | **128** | **6488** | **25** | **A. Tempia Calvino et al.** | **LUT mapping with Boolean decomposition** |
|  **Sine**  |  **24**  | **25**  | **675550**  | **10** | **H. Wang and P. Wang** | **EasyLS** |
|  **Square-root**  |  **128**  | **64**  | **24421**  | **153** | **H. Wang and P. Wang** | **EasyLS** |
|  **Square**  |  **64**  | **128**  | **3700**  | **10** | **H. Wang and P. Wang** | **EasyLS** |

Random-Control Benchmarks

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
|  Round-robin arbiter | 256 | 129  | 370  | 5 | T. Besson | ABC-DE: ABC Design Explorer |
|  Alu control unit   |  7  | 26 | 25   | 2  | A. Grosnit, C. Feng, X. Li, et al. | NAILS |
|  Coding-cavlc    |  10  | 11   | 60   | 3 |  T. Besson | ABC-DE: ABC Design Explorer |
|  Decoder  | 8  | 256   | 264   | 2  | L. Machado and J. Cortadella | Support-Reducing Decomp |
|  I2c controller  |  147  | 142  | 193 | 3 | T. Besson | ABC-DE: ABC Design Explorer |
|  **Int to float converter**  |  **11**  | **7**  | **19**  | **3**  |  **T. Besson** | **ABC-DE: ABC Design Explorer** |
|  **Memory controller**  |  **1204**  | **1231**  | **1871**  | **5** | **H. Wang and P. Wang** | **EasyLS** |
|  Priority encoder  | 128 | 8  | 119 | 4 |  T. Besson | ABC-DE: ABC Design Explorer |
|  Lookahead XY router | 60 | 30 | 25 | 3 | T. Besson | ABC-DE: ABC Design Explorer |
|  **Voter**  |  **1001**  | **1** | **1336**  | **11** | **H. Wang and P. Wang** | **EasyLS** |

MtM Benchmarks 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Sixteen | 117	| 50 |	3387001	| 14 | T. Besson | ABC-DE: ABC Design Explorer |
| Twenty  | 137 | 60 |	4381634 | 14 |  T. Besson | ABC-DE: ABC Design Explorer |
| Twentythree | 153 | 68 | 4913996 | 15 |  T. Besson | ABC-DE: ABC Design Explorer |

### List of Participants and Methods
| Authors' name | Authors' affiliation | Synthesis method| Description |
| ------------- | ------------- | ------------- | ------------- | 
| Robert K. Brayton & Alan Mishchenko| UC Berkeley | ABC Extreme Mapper | Interactive optimization using a variaty of optimization scripts in [ABC](https://github.com/berkeley-abc/abc)|
| Luca Amaru | EPFL | MIG + ABC Mapper | Based on rewriting algorithms presented in [Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Majority-Inverter Graph: A Novel Data-Structure and Algorithms for Efficient Logic Optimization. DAC 2014: 194:1-194:6](https://infoscience.epfl.ch/record/211244/files/07293649.pdf)|
| Alan Mishchenko| UC Berkeley | ABC Ultimate Mapper | Based on lazy man synthesis using recorded [database](http://people.eecs.berkeley.edu/~alanmi/temp5/rec6Lib_final_filtered3_recanon.aig). ABC script: "rec_start rec6Lib_final_filtered3_recann.aig; read file.aig; resyn2; resyn2; if -y -K 6; if -y -K 6;" // repeat until no further improvement|
| Winston Haaswijk et al. | EPFL | MIG LUT Mapping | Based on resynthesis algorithms presented in Winston Haaswijk, Mathias Soeken, Luca Gaetano Amarù, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: LUT Mapping and Optimization for majority-inverter graphs. IWLS 2016 |
| Gai Liu & Zhiru Zhang | Cornell University | PIMap | Based on parallelized iterative improvement mapping presented in [Gai Liu and Zhiru Zhang: A parallelized iterative improvement approach to area optimization for LUT-based technology mapping. FPGA, 2017](http://delivery.acm.org/10.1145/3030000/3021735/p147-liu.pdf?ip=198.182.47.47&id=3021735&acc=CHORUS&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1535664503_83b042899a419486179f19e4dbd2e1ca) |
| Alan Mishchenko et al. | UC Berkeley | SAT LUT Mapper | Based on SAT based remapping algorithm. ABC script (the file.blif is best known results from 2015): "read file.blif; &satlut -N 64 -C 10000"|
| Luca Amaru et al. | Synopsys Inc. | Exact Delay synthesis | Based on rewriting using exact delay database as presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Pierre-Emmanuel Gaillardon, Janet Olson, Rober Brayton, Giovanni De Micheli: Enabling Exact Delay Synthesis. ICCAD, 2017](https://people.eecs.berkeley.edu/~alanmi/publications/2017/iccad17_eds.pdf)|
| L. Machado and J. Cortadella | Universitat Politècnica de Catalunya | Support-Reducing Decomp | Based on the algorithm presented in [Lucas Machado and Jordi Cortadella: Support-Reducing Functional Decomposition for FPGA Technology Mapping. IWLS, 2018](http://www.cs.upc.edu/~jordicf/gavina/BIB/files/iwls2018_FPGA.pdf) and in [Lucas Machado and Jordi Cortadella: Support-Reducing Decomposition for FPGA Mapping. TCAD, 2018](https://ieeexplore.ieee.org/document/8509141) |
| L. Amaru et al. | Synopsys Inc. | Boolean Resynthesis | Boolean resynthesis techniques. Algorithm presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Janet Olson, Robert K. Brayton, Giovanni De Micheli: Improvements to Boolean resynthesis. DATE, 2018](https://people.eecs.berkeley.edu/~alanmi/publications/2018/date18_resyn.pdf)|
| E. Testa et al. | EPFL and Synopsys Inc. | Boolean Methods | Algorithm presented in [Eleonora Testa, Luca Gaetano Amarù, Mathias Soeken, Alan Mishchenko, Patrick Vuillod, Jiong Luo, Christopher Casares, Pierre-Emmanuel Gaillardon, Giovanni De Micheli: Scalable Boolean Methods In A Modern Synthesis Flow. DATE, 2019](https://msoeken.github.io/papers/2019_date_2.pdf)|
| I. Lemberski et al. | Ventspils University for Applied Sciences | Resubstitution | Based on the resubstitution method presented in [Igor Lemberski, Artjoms Suponenkovs, Marina Uhanova: LUT-Oriented Asynchronous Logic Design Based on Resubstitution. DTIS, 2019](https://ieeexplore.ieee.org/document/8734973) |
| Xing Li et al. | Huawei Noah's Ark Lab | HIMap | Based on heuristic and iterative mapping combined with improved logic optimization and post-mapping methods in ABC presented in [Xing Li, Lei Chen, Fan Yang, Mingxuan Yuan, Hongli Yan, and Yupeng Wan: HIMap: A Heuristic and Iterative Logic Synthesis Approach. DAC, 2022](https://dl.acm.org/doi/10.1145/3489517.3530460) |
| L. Amaru et al. | Synopsys Inc. | LUT-optimization | Based on LUT optimization presented in [Luca Amarú, Vinicius Possani, Eleonora Testa, Felipe Marranghello, Christopher Casares, Jiong Luo, Patrick Vuillod, Alan Mishchenko, Giovanni De Micheli: LUT-Based Optimization For ASIC Design Flow. DAC, 2021](https://ieeexplore.ieee.org/document/9586132) |
| S. Jang and A. Mishchenko | UC Berkeley | iMap | A portfolio logic synthesis system based on [ABC](https://github.com/berkeley-abc/abc) |
| Longfei Fan and Chang Wu | Fudan University | scaleSyn mapper | Area-oriented technology mapping combined with pre- and post-mapping logic optimization methods in ABC |
| Alessandro Tempia Calvino | EPFL | XAG optimization | Based on XAG optimization and post-mapping methods in ABC |
| Rafael Calcada & Andre Reis | UFRGS | Priority Cut mapping | AIG optimization using commands 'dc2' and 'b -l' from [ABC](https://github.com/berkeley-abc/abc) followed by Priority Cut mapping with new heuristics for area and delay estimation |
| A. Grosnit, C. Feng, X. Li, et al. | Huawei Noah's Ark Lab | NAILS | A collection of heuristic aided Bayesian Optimization and heuristic methods from AI4EDA team of Noah's Ark Lab |
| W. L. Neto, L. Amaru, et al. | University of Utah and Synopsys | Improved LUT optimization | Improving LUT-based optimization for ASIC presented in [W. L. Neto, L. Amarú, V. Possani, P. Vuillod, J. Luo, A. Mishchenko, and P.E. Gaillardon: Improving LUT-based optimization for ASIC. DAC, 2022](https://dl.acm.org/doi/abs/10.1145/3489517.3530461) |
| T. Besson | Rapid Silicon | ABC-DE | ABC Design Exploration performing parallel exploration of incrementally built ABC scripts |
| J. Yuan, J. Ye, et al. | Huawei Noah's Ark Lab and Shanghai Jiao Tong University | EasyRL | Reinforcement Learning-based methods |
| F. Reichl, F. Slivovsky, S. Szeider | TU Wien | Exact Subcircuit Synthesis | QBF and SAT-based exact synthesis of subcircuits applied to previous best results presented in [F.-X. Reichl, F. Slivovsky, and S. Szeider: Circuit Minimization with QBF-Based Exact Synthesis, AAAI, 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25524) |
| Hexi Wang and Peiyu Wang | Shanghai Jiao Tong University and Huawei Noah's Ark Lab | EasyLS | Based on reinforcement learning and an enhanced LUT-based mapping algorithm presented in [J. Yuan et al.: EasySO: Exploration-enhanced Reinforcement Learning for Logic Synthesis Sequence Optimization and a Comprehensive RL Environment, ICCAD, 2023](https://ieeexplore.ieee.org/document/10323973) and [P. Wang et al.: EasyMap: Improving Technology Mapping via Exploration-Enhanced Heuristics and Adaptive Sequencing, ICCAD, 2023](https://ieeexplore.ieee.org/document/10323973) |
| A. Tempia Calvino et al. | EPFL and UC Berkeley | LUT mapping with Boolean decomposition | Based on the delay-driven LUT mapping algorithm with Boolean decomposition presented in [A. Tempia Calvino, A. Mishchenko, G. De Micheli, and R. Brayton: Practical Boolean Decomposition for Delay-driven LUT Mapping, IWLS, 2024](https://arxiv.org/pdf/2406.06241) |
| A. Costamagna et al. | EPFL and UC Berkeley | Information graph-based resubstitution | Based on the paper A. Costamagna, A. Tempia Calvino, A. Mishchenko, and G. De Micheli: Area-Oriented Resubstitution For Networks of Look-Up Tables, IWLS, 2024 |
