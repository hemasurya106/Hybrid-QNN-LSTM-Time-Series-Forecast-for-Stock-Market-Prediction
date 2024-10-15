Hybrid Quantum-Classical LSTM for Stock Price Prediction

This project demonstrates a hybrid quantum-classical Long Short-Term Memory (LSTM) model for stock price prediction. It combines the strengths of classical LSTM networks with the potential of quantum computing to enhance prediction accuracy.

Model Architecture

The model consists of the following components:

Classical LSTM: A standard LSTM layer to capture temporal dependencies in the stock price data.
Quantum Layer: A variational quantum circuit implemented using PennyLane, acting as a non-linear transformation layer.
Classical Dense Layer: A fully connected layer to produce the final stock price prediction.
Requirements

Python 3.x
PyTorch
PennyLane
torchvision
Pandas
NumPy
Matplotlib
Scikit-learn
Installation

Install the required libraries using pip:

pip install torch torchvision pennylane pandas numpy matplotlib scikit-learn
Usage

Prepare the data:

Obtain historical stock price data in CSV format.
Ensure the data includes a column named "Close" (or modify the code accordingly).
Place the CSV file in the same directory as the code or provide the correct file path.
Run the code:

Execute the Python code to train the hybrid model and generate predictions.
The code includes data normalization, sliding window data preparation, model definition, training, and evaluation.
Visualize results:

The code generates a plot comparing the predicted and actual stock prices.
The R-squared score is calculated to evaluate the model's performance.
Note

This is a basic example and can be further improved by exploring different quantum circuit architectures, hyperparameter tuning, and data preprocessing techniques.
The choice of quantum device (simulator or real hardware) can impact the results.
Consider adjusting the number of qubits, LSTM units, and other parameters for optimal performance.
