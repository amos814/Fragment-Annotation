### Fragment-Annotation

The main report of this project can be found in [Fragment Annotation](https://docs.google.com/presentation/d/1cAIJ-VXAA79IifDq4fs7Qm0XIYtDh1224waXSKOOgZI/edit?usp=sharing).

#### Motivation
In this proejct, we try to solve a different task 'Fragment Annotation' based on the recent work of the building plasmid. While making the plasmid, rather than synthesize the whole plasmid, we can tempt to use the assembly method to create them. However, in order to apply the assembly method, we have to reuse the existing fragment in order to lower down the cost of the synthesis.

We formulate a task, fragment annotation, which is basically try to find the reuse 100% match fragment of the given plasmid in order to lower the cost. We designed the greedy based method in three diffrent kind of version, which are vannila, iteratively, one-shot iteratively. Finally, in the cost analysis, we can tell find a huge drop of the cost which shows the effectiveness of our method.

#### Usage

The main algorithm is written in the jupyter notebook. Also, the BLAST searching method is written in the`segment()` function which is in `annotate.py`.

In order to setup the python enviornment, we can follow the instruction in the `requirements.txt` to install the required packages.
