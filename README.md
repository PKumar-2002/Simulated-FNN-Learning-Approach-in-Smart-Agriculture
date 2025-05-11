# 🌾 Federated Neural Network for Smart Agriculture

A PyTorch-based simulation of federated learning for crop recommendation. Compare decentralized training across 5 clients against a centralized neural network baseline.

## 🚀 Features

- **Federated Learning Simulation**  
  Five distributed clients train a Feedforward Neural Network (FNN) on local data.  
- **Centralized Baseline**  
  Benchmark decentralized results against a standard, centralized ANN.  
- **Crop Recommendation**  
  Uses the popular `Crop_recommendation` dataset to predict the most suitable crop based on soil and weather parameters.  
- **Metrics & Logging**  
  Track accuracy, loss, and communication rounds with clear matplotlib plots and CSV logs.

## 📈 Results

| Model Type      | Accuracy (%) | Rounds/Epochs |
| --------------- | -----------: | ------------: |
| Federated FNN   |        94.1  | 50 rounds     |
| Centralized ANN |        87.8  | 50 epochs     |

“Cultivating intelligence—one crop at a time.” 🌱

