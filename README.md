# criticData
Critic data generation for SVAMP dataset

Semester project of [Emilien Seiler](mailto:emilien.seiler@epfl.ch), Master in Computational Science and Engineering at EPFL. 
Project in Artificial Intelligence Laboratory (LIA).

## Structure

This is the structure of the repository:

- `create_incorrect.ipynb`: notebook to create critic data
- `SVAMP.json`: SVAMP data
- `dev.csv`: dev data
- `train.csv`: train data
- `SVAMP_critic_data.json`: SVAMP critic data generated
- `dev_critic_data.json`: Dev critic data generated
- `train_critic_data.json`: Train critic data generated

## Informations

5 type of critic data are created:
- No (when it is the true answer)
- operation in position ... is incorrect
- number in position ... is incorrect
- add an operation
- remove an operation
