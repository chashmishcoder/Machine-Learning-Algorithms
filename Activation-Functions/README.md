# Activation Function Demonstration

This project demonstrates the importance of activation functions in neural networks by comparing the performance of models with and without activation functions.

## Setup

1. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the demonstration:
   ```
   python activation_function_demo.py
   ```

## What to Expect

The script will:
1. Train two models on a non-linear classification task (the moons dataset)
   - One model without activation functions in hidden layers
   - One model with ReLU activation functions in hidden layers
   
2. Compare and visualize:
   - Training and validation accuracy curves
   - Decision boundaries for both models
   - Final test accuracy

3. Provide an explanation of why activation functions are crucial

## Key Concepts Demonstrated

1. **Linear vs. Non-linear Representation**: Without activation functions, neural networks can only represent linear transformations, regardless of depth.

2. **Approximation Power**: Networks with activation functions can approximate complex, non-linear functions.

3. **Feature Learning**: Activation functions enable hierarchical feature learning in deep networks.

4. **Classification Performance**: The difference in accuracy on non-linear data demonstrates how activation functions enhance model capabilities. 
