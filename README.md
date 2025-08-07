# Experiments on Neural Network Pruning and It’s Effect on Transfer Learning

This project implements a neural network from scratch using NumPy to learn the XOR logic gate. After training, the model undergoes weight pruning to reduce unnecessary connections while preserving performance. The pruned model is then used for transfer learning on OR and AND logic gates, demonstrating how learned weights can be reused for related tasks.

## Description

- Neural network architecture: 2 input neurons, 2 hidden neurons, 1 output neuron.
- Implements forward propagation, backpropagation, and gradient descent manually.
- Pruning is applied to reduce model complexity.
- Transfer learning is used to fine-tune the pruned model on OR and AND gates.
- Evaluation is done using cost plots and classification reports.

## Installation

Install the required Python libraries:

```bash
pip install numpy matplotlib scikit-learn
```

## How to Run

Clone the repository and run the script:
(You can use google colab to run this script) 
```bash
git clone https://github.com/YOUR_USERNAME/xor-transfer-learning-pruning.git
cd xor-transfer-learning-pruning
python xor_pruning_transfer_learning.py
```

## Files

- `xor_pruning_transfer_learning.py`: Main script with all logic for training, pruning, and transfer learning.
- `README.md`: Project documentation.


