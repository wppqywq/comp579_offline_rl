# Comparison of Offline RL Algorithms on CartPole

Autor: Claire Yang

This Github repository[https://github.com/wppqywq/comp579_offline_rl] compares three offline reinforcement learning algorithms (Behavior Cloning, Offline DQN, and Conservative Q-Learning) on the CartPole environment using datasets of varying quality.

## Project Structure

- `algorithm.ipynb`: Main notebook containing implementations and comparisons of BC, Offline DQN, and CQL algorithms
- `data_gen.ipynb`: Notebook for generating and preprocessing the three datasets (expert, random, and mixed)
- `xxx_data.npz`: Pre-collected dataset
- `xxx_data_metadata.json`: Metadata for the dataset
- `comp_579_final_report.pdf`: Detailed report analyzing the results
- `579_final_pre.mp4`: The presentation video for the final project.

## Requirements

```gymnasium
torch≥1.13.0
numpy
matplotlib
pandas
d3rlpy≥2.0.2
tabulate
seaborn
tqdm 
```
