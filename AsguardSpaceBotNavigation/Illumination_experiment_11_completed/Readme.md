# The experiment 11 

In this experiment we have aimed for a higher performance, included orientation in the goals and added a newer version of the rover model.

It is an incremental experiment, which currently is the only type of experiment supported.

Samples execute one mission at a time. The missions are increasingly complex and there are 3 missions.

No results from previous experiments have been reused.

The target performance was achieved around sample 6500.

experiment_setup:
  initial_population_size: 600
  num_mutations: 20000
  num_replicates: 5
  reuse_results: false
  reuse_results_exp_conf: ""
  mode: "incremental"
  evolution_stats_n_best: 5
  goal_n_best: 0.75
  bpm_dims:
    motion_planner: "mSpeedForward"
    traversability: "maximum_slope"
