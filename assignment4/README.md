# CS 7641 Assignment 4: Markov Decision Processes

In this repository, we applied Policy Iteration, Value Iteration and Q-Learning to solve two MDPs.

## Output
Output CSVs and images are written to `./output` and `./output/images` respectively. Sub-folders will be created for each RL algorithm (PI, VI, and Q) as well as one for the final report data.

If these folders do not exist the experiments module will attempt to create them.

## Get Started

The run_experiment script can be use to generate plots via:

```
python run_experiment.py --plot
```

Since the files output from the experiments follow a common naming scheme this will determine the problem, algorithm,
and parameters as needed and write the output to sub-folders in `./output/images` and `./output/report`.

