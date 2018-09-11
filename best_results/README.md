# Best LUT-6 Implementations - 2018
The best LUT-6 implementations keep track of the best results of LUT-6 mapped benchmarks, both for size (# of LUTs) and depth (# of levels). 

### Best results for LUT-6 count

**Arithmetic Benchmarks** 

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Adder | 256  | 129  | 192 | 64| Winston Haaswijk  |MIG LUT Mapper |
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| Divisor  | 128 | 128   | 3268   |  1208  |  Gai Liu & Zhiru Zhang |  PIMap |
|  **Hypotenuse**  |  **256**  | **128**   | **40385**   | **4527**  |  **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  **Log2**  |  **32**  | **32**  | **6570** | **119**  |  **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  Max  |  512  | 130  | 523  | 189 |  Gai Liu & Zhiru Zhang |  PIMap |
|  Multiplier  |  128  | 128  | 4923  | 90 |   Alan Mishchenko et al. |  SAT LUT Mapper |
|  **Sine**  |  **24**  | **25**  | **1228**  | **55** |  **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  **Square-root**  |  **128**  | **64**  | **3076**  | **1106** |  **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  **Square**  |  **64**  | **128**  | **3244**  | **74** |   **Luca Amaru et al.** |  **Boolean Resynthesis** |

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
|  **Round-robin arbiter**  |  **256**   |  **129**   |  **403**   |  **23** |  **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  Alu control unit   |  7  | 26   | 27   | 2  | Gai Liu & Zhiru Zhang |  PIMap |
|  **Coding-cavlc**    |  **10**  | **11**   | **72**   | **4**  | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Decoder**  | **8**  | **256**   | **264**   | **2**  | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **I2c controller**  |  **147**  | **142**  | **211** | **7**  | **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  **Int to float converter**  |  **11**  | **7**  | **26**  | **4**  | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Memory controller**  |  **1204**  | **1231**  | **2117**  | **22** | **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  **Priority encoder**  |  **128**  | **8**  | **108** | **26** | **Luca Amaru et al.** |  **Boolean Resynthesis** |
|  Lookahead XY router  |  60  | 30  | 52  | 6 | Gai Liu & Zhiru Zhang |  PIMap |
|  **Voter**  |  **1001**  | **1**  | **1297**  | **17** | **Luca Amaru et al.** |  **Boolean Resynthesis** |

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
| **Adder** | **256**  | **129**  | **470**  | **5**| **L.  Amaru et al.** |**Exact Delay Synthesis** |
| Barrel shifter  | 135 |128  | 512  |4  | R. K. Brayton & A. Mishchenko|ABC Extreme Mapper|
| **Divisor**  | **128** |**128**  |**26914** | **228** | **L.  Amaru et al.** |**Exact Delay Synthesis** |
| **Hypotenuse** | **256** |**128**  | **151442** |**567** | **L.  Amaru et al.** |**Exact Delay Synthesis** |
|  **Log2**  |  **32**  | **32**  | **9210** | **55**  |    **L.  Amaru et al.** |**Exact Delay Synthesis** |
|  **Max** |  **512**  | **130**  | **857** | **10** |  **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
| **Multiplier** | **128** |**128** |**7274** |**27**| **L.  Amaru et al.** |**Exact Delay Synthesis** |
|  **Sine**  |  **24**  | **25**  | **487941**  | **12** | **L.  Amaru et al.** |**Exact Delay Synthesis** |
|  **Square-root**  |  **128**  | **64**  | **27265**  | **241** |  **L.  Amaru et al.** |**Exact Delay Synthesis** | 
|  **Square**  |  **64**  | **128**  | **3967**  | **11** |  **L.  Amaru et al.** |**Exact Delay Synthesis** | 

**Random-Control Benchmarks**

| Benchmark name | Inputs | Outputs | LUT-6 count | Levels | Authors | Method |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
|  **Round-robin arbiter** | **256** | **129**  | **2243**  | **5** | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  Alu control unit   |  7  | 26   | 27   | 2  | Gai Liu & Zhiru Zhang |  PIMap |
|  **Coding-cavlc**    |  **10**  | **11**   | **75**   | **3** |  **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Decoder**  | **8**  | **256**   | **264**   | **2**  | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **I2c controller**  |  **147**  | **142**  | **242** | **3** |  **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Int to float converter**  |  **11**  | **7**  | **31**  | **3**  |  **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Memory controller**  |  **1204**  | **1231**  | **2484**  | **6** | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Priority encoder**  |  **128**  | **8**  | **152** | **4**|  **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Lookahead XY router** | **60** |**30** |**54** | **4**|**L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |
|  **Voter**  |  **1001**  | **1**  | **1450**  | **12** | **L. Machado and J. Cortadella** |  **Support-Reducing Decomp** |

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
| Luca Amaru et al. | Synopsys Inc. | Exact Delay synthesis | Based on rewriting using exact delay database as presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Pierre-Emmanuel Gaillardon, Janet Olson, Rober Brayton, Giovanni De Micheli: Enabling Exact Delay Synthesis. ICCAD, 2017](https://people.eecs.berkeley.edu/~alanmi/publications/2017/iccad17_eds.pdf)|
| L. Machado and J. Cortadella | Universitat Politècnica de Catalunya | Support-Reducing Decomp | Based on the algorithm presented in Lucas Machado and Jordi Cortadella: Support-Reducing Functional Decomposition for FPGA Technology Mapping. IWLS 2018|
| L. Amaru et al. | Synopsys Inc. | Boolean Resynthesis | Boolean resynthesis techniques. Algorithm presented in [Luca Gaetano Amarù, Mathias Soeken, Patrick Vuillod, Jiong Luo, Alan Mishchenko, Janet Olson, Robert K. Brayton, Giovanni De Micheli: Improvements to Boolean resynthesis. DATE 2018](https://people.eecs.berkeley.edu/~alanmi/publications/2018/date18_resyn.pdf)|


