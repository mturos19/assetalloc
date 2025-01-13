# RL Asset Allocation

## Overview
This repository contains the code for a Reinforcement Learning (RL) based asset allocation project. The project utilizes custom gym environments and advanced RL algorithms to optimize portfolio management strategies.

## Features
- Custom `PortfolioEnv` environment for simulating portfolio optimization.
- Implementation of PPO algorithm using `stable-baselines3`.
- GPU monitoring during training with `GPUMonitorCallback`.

## Installation
Clone the repository and install the dependencies:

## Usage
1. **Prepare Data**: Ensure your data is in the correct format and located at `data/processed/merged_data.csv`.
2. **Train Model**: Run `train.py` to start training the RL model.
3. **Evaluate**: Use the trained model to evaluate portfolio strategies.

## Project Structure
- `env.py`: Contains the `PortfolioEnv` class for the custom gym environment.
- `train.py`: Script to train the RL model using PPO.
- `models/`: Directory to save trained models.
- `data/`: Directory for input data.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For questions, please contact [markturosy2k@gmail.com].
