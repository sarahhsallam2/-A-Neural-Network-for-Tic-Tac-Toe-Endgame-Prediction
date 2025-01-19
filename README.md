# -A-Neural-Network-for-Tic-Tac-Toe-Endgame-Prediction

## 🧠 Project Overview
This project consists of three main tasks:
1. **Data Selection and Preprocessing**: Selecting and preparing the **tic-tac-toe endgame** dataset for training.
2. **Neural Network Implementation and Weight Optimization**: Implementing a neural network and optimizing its weights using **Genetic Algorithms (GA)**.
3. **Backpropagation Implementation**: Replacing GA-based weight updates with **backpropagation** to train the network.

The goal of the project is to predict the outcome of a Tic-Tac-Toe game based on the configuration of the board. This task involves binary classification (win or no win for 'X').

## 📊 Dataset
The dataset used in this project is the **tic-tac-toe endgame dataset** from UCI Machine Learning Repository:  
[**Tic-Tac-Toe Endgame Dataset**](https://archive.ics.uci.edu/dataset/101/tic+tac+toe+endgame)  
The dataset includes all possible configurations of a Tic-Tac-Toe board at the end of a game.

### Key Features:
- **Board Positions**: 9 features representing the state of each cell on the 3x3 board (x, o, or empty).
- **Class Label**: Binary classification indicating whether 'X' wins or not (1 for win, 0 for no win).

## 🛠️ Technologies and Tools Used
- **Programming Languages**: Python
- **Algorithms**: Genetic Algorithm, Backpropagation
- **Data Preprocessing**: One-hot encoding, Data cleaning, Data splitting (training, validation, test)
- **Visualization**: Matplotlib for visualizing data distributions and performance graphs

## 📝 How the Neural Network Works
1. **Data Preprocessing**
   - The dataset is loaded and cleaned using Pandas, followed by one-hot encoding of board positions.
   - The data is split into training, validation, and test sets (70%, 20%, 10%).

2. **Genetic Algorithm for Optimization**
   - Neural network weights are initialized randomly.
   - A genetic algorithm is applied to optimize the network by performing selection, crossover, and mutation of the neural network population.

3. **Backpropagation for Training**
   - Backpropagation replaces the genetic algorithm for training, allowing the network to adjust weights using error gradients.
   - The network is trained for several epochs, with performance metrics (accuracy, error) recorded.

## 🔍 Results
- **Training Accuracy**: ~73.2% with GA optimization.
- **Testing Accuracy**: Evaluated after training to assess how well the network generalizes to new data.

## 📈 Visualizations
- **Training and Validation Error Plots**: A line plot visualizing error during training.
- **Performance Metrics**: Accuracy and error rates are displayed at the end of the training process.

## 🤝 Team Members
- **Sara Khaled**
- **Lojain Elsalnty**
- **Youssed Hossam**
- **Ahmed Mosad**
- **Omar Yasser Ramadan**

