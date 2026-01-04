# Link Prediction on International Trade Network 🌍📊

A machine learning project that predicts potential trade relationships between countries using graph neural networks and network analysis techniques on international trade data.

## 📋 Overview

This project applies link prediction algorithms to international trade networks to identify potential future trade partnerships between countries. By analyzing historical trade patterns and network structures, the model can forecast which countries are likely to establish new trade relationships, helping economists, policymakers, and businesses understand global trade dynamics.

## 🎯 Objectives

- Analyze the structure and patterns of the international trade network
- Implement various link prediction algorithms on trade data
- Predict potential future trade relationships between countries
- Evaluate model performance using appropriate metrics
- Provide insights into global trade dynamics and opportunities

## ✨ Key Features

- **Network Analysis**: Comprehensive analysis of international trade network topology
- **Multiple Algorithms**: Implementation of various link prediction techniques
- **Performance Evaluation**: Comparison of different models using accuracy, precision, recall, and AUC-ROC
- **Visualization**: Interactive visualizations of trade networks and predictions
- **Scalable Approach**: Handles large-scale international trade datasets

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **NetworkX**: Graph creation and analysis
- **Scikit-learn**: Machine learning algorithms
- **Pandas & NumPy**: Data manipulation and numerical operations
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment

## 📊 Methodology

### 1. Data Collection & Preprocessing
- International trade data from World Bank, UN Comtrade, or similar sources
- Data cleaning and normalization
- Graph construction from trade relationships

### 2. Network Analysis
- Degree distribution analysis
- Centrality measures (betweenness, closeness, eigenvector)
- Community detection
- Network density and clustering coefficients

### 3. Link Prediction Algorithms
- **Common Neighbors**: Based on mutual trading partners
- **Jaccard Coefficient**: Normalized common neighbors
- **Adamic-Adar Index**: Weighted common neighbors
- **Preferential Attachment**: Based on node degrees
- **Resource Allocation**: Network flow-based approach
- **Graph Neural Networks (GNN)**: Advanced deep learning approach

### 4. Model Evaluation
- Train-test split on temporal data
- Cross-validation
- Performance metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7 or higher
Jupyter Notebook or JupyterLab
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Aishwary0402/Link-Prediction-On-International-Trade-Network.git
cd Link-Prediction-On-International-Trade-Network
```

2. Install required packages:
```bash
pip install numpy pandas matplotlib seaborn networkx scikit-learn jupyter
```

### Running the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `New.ipynb` and run the cells sequentially

3. Review the `Graph_project.pdf` for detailed methodology and results

## 📁 Project Structure

```
Link-Prediction-On-International-Trade-Network/
├── New.ipynb              # Main Jupyter notebook with implementation
├── Graph_project.pdf      # Detailed project report and methodology
└── README.md             # Project documentation
```

## 📈 Results

The project demonstrates:
- Identification of key trading hubs and their influence on global trade
- Successful prediction of potential new trade relationships
- Comparison of different link prediction algorithms
- Insights into factors that influence trade partnership formation

## 🔍 Key Insights

- **Network Structure**: International trade networks exhibit scale-free and small-world properties
- **Predictive Patterns**: Geographic proximity, economic similarity, and existing trade partnerships are strong predictors
- **Algorithm Performance**: Graph-based algorithms combined with economic indicators yield the best predictions
- **Policy Implications**: Results can inform trade policy and international relations strategies

## 📊 Potential Applications

- **Economic Forecasting**: Predict future trade flows and economic relationships
- **Policy Planning**: Assist governments in identifying strategic trade partnerships
- **Business Intelligence**: Help companies identify new markets and opportunities
- **Supply Chain Optimization**: Improve global supply chain resilience
- **Risk Assessment**: Identify vulnerabilities in international trade networks

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📚 References

- International trade datasets (World Bank, UN Comtrade)
- Link prediction algorithms in social networks
- Graph neural networks for network analysis
- Economic indicators and trade theory

## 📝 Future Work

- Incorporate temporal dynamics and time-series analysis
- Add more economic indicators (GDP, trade agreements, political stability)
- Implement advanced GNN architectures (GraphSAGE, GAT)
- Real-time prediction system with updated trade data
- Interactive web dashboard for visualizing predictions

## 🙏 Acknowledgments

- Thanks to international trade data providers
- Research papers on link prediction and network analysis
- Open-source community for amazing tools and libraries

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please open an issue on GitHub.

---

**Note**: This is an academic/research project. Predictions should be interpreted as probabilistic forecasts and not definitive future outcomes.
