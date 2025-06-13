# Projet-Optimization-for-Machine-Learning

### Subject : Learning Rate Sensitivity in Adaptive Optimizers

Adaptive optimization algorithms are widely used in deep learning for their fast convergence and robustness. Despite this adaptivity, the choice of the initial learning rate remains a crucial hyperparameter that significantly affects convergence behavior, training time and generalization performance. In this work, we study the effect of varying the initial learning rate on these optimizers when training a CNN on the CIFAR-10 dataset. Using a consistent experimental setup, we compare performance across accuracy and training time, highlighting practical trade-offs and providing tuning recommendations. 

The project is structured as follows:

- `simple_studies/`: Implements the Fixed Grid Search Experimental Protocol across optimizers and learning rates.
- `optuna_study/`: Explores Hyperparameter Optimization with Optuna to automatically search for optimal learning rates.

### Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/super-pingouin/Projet-Optimization-for-Machine-Learning.git
cd Projet-Optimization-for-Machine-Learning
pip install -r requirements.txt
