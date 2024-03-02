
# Deep Reinforcement Learning 🤖🎮

![Python](https://img.shields.io/badge/python-v3.8-blue)
![License](https://img.shields.io/badge/license-GPLv3-blue.svg)

This project utilizes a notebook to train a model for balancing a matchstick on a box, leveraging Deep Q-Learning. It's an experiment in applying reinforcement learning techniques to solve the classic "CartPole" problem from OpenAI's Gym.

## Overview 📖

The goal is to develop an agent capable of maintaining a pole in an upright position as long as possible by moving the cart on which it's mounted. This project is an introduction to the concepts of Deep Q-Learning, including experience replay and the use of a neural network to approximate Q-values.

## Getting Started 🚀

To run this project, you will need:

- Python 3.8 or above
- An environment manager (e.g., conda or venv)
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository to your local machine.
2. Create a virtual environment:

```bash
python -m venv venv
```

3. Activate the virtual environment:

- On Windows: `venv\Scripts\activate`
- On Unix or MacOS: `source venv/bin/activate`

4. Install the required packages:

```bash
pip install -r requirements.txt
```

5. Open the notebook `cartpole.ipynb` in Jupyter Notebook or JupyterLab and follow the instructions.

## Technologies Used 🛠️

- [Python](https://www.python.org/): The main programming language used.
- [OpenAI Gym](https://gym.openai.com/): Provides the CartPole environment.
- [TensorFlow](https://www.tensorflow.org/): Used for creating and training the neural network.

## License 📄

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
