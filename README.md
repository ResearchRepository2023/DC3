# DC3 (Cognitive Complexity CC Sonar ++)
DC3 Metric CC Sonar ++

This repository contains the data related to the "Developer-Centric Cognitive Complexity (DC3)" CC Sonar ++: A Metric for Evaluating Code Comprehension Difficulty. The work behind this metric investigates the relationship between code complexity and the comprehension difficulty experienced by programmers when analyzing code.

Dataset
The dataset used in this work is included in the repository. It consists of a set of programs, varying in complexity, that were used for the experiment. Each program is labeled with the corresponding code complexity metrics, including McCabe and Halstead metrics, as well as cognitive complexity metrics obtained from SonarQube. The dataset also contains the EEG data captured during the experiment, which represents the cognitive load experienced by the programmers.

The dataset comprises the following:
a) Dataset Description file
b) Tools used to estimate code complexities
**c) Programs used for evaluation. The programs were divided into coherent non-overlapping regions that enable us to compute various complexity metrics. The division can be arbitrary if it meets the condition of not breaking any coherent sequence of lines in the code and if it is feasible to compute complexity metrics. 
**
d) A link to the Matlab files for each volunteer
