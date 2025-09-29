# Music Genre Classification Using Machine Learning

This project explores the effectiveness of different machine learning algorithms and feature selection in genre classification. Using the GTZAN dataset, we implemented four models to classify music genres based on audio features extracted with the openSMILE package. The goal was to identify the most accurate model and the optimal number of parameters for genre recognition.

## Dataset

- **Source**: GTZAN Genre Collection
- **Size**: 1,000 audio tracks, each 30 seconds long
- **Genres**: 10 distinct genres (e.g., blues, classical, jazz, rock)
- **Preprocessing**: Extracted 6,000 audio features per track using openSMILE.

## Models

Four machine learning models were tested:

1. **Support Vector Machine (SVM)**
2. **Random Forest**
3. **Stack Ensemble**
4. **Multilayer Perceptron (MLP)**

## Methodology

- **Training/Testing Split**: 80% training, 20% testing
- **Feature Selection**: Models were tested with different subsets of parameters to analyze the effect on classification accuracy.
- **Evaluation Metrics**: Accuracy and confusion matrices were used to assess performance.

## Results

- **Best Model**: Multilayer Perceptron (MLP)
- **Highest Accuracy**: 89% classification rate using 2,000 to 3,000 parameters.
- **Insights**: The MLP model outperformed other models, suggesting that deep learning architectures can handle complex audio feature spaces effectively in genre classification tasks.


## Contributing

We welcome contributions! Please fork the repository and make a pull request for any improvements or additional models.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments

- The GTZAN dataset for providing genre-classification data
- The openSMILE package for robust feature extraction tools

---

