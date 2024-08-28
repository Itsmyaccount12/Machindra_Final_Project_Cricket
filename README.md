# Cricket Shot Classification Using CNNs

## Overview
This project explores the use of Convolutional Neural Networks (CNNs) to classify different types of cricket shots from images. The project uses deep learning and computer vision techniques, leveraging the PyTorch framework to train and evaluate models. The models developed in this project aim to classify cricket shots such as legglance-flick, pullshot, sweep, and drive.

## Project Structure
- **Abstract:** An overview of the project's objectives, methodology, and key findings.
- **Acknowledgements:** Credits to individuals and organizations that supported the project.
- **Introduction:** Provides context on the problem, research questions, and objectives.
- **Background:** Discusses the dataset, literature review, and relevant algorithms.
- **Methodology:** Details the tools, techniques, and project plan used in the research.
- **Results and Conclusion:** Summarizes the model performance and insights derived from the experiments.
- **Legal, Ethical, and Professional Issues:** Explores the implications of using image data in sports analytics.
- **References:** Cites the sources referenced throughout the project.
- **Appendices:** Includes the code used to implement the project.

## Dataset
The dataset used contains images representing four classes of cricket shots. The images were preprocessed and augmented to enhance model performance. The data was split into training and testing sets with an 80:20 ratio.

## Models
Three different CNN models were implemented and evaluated:
1. **Simple CNN:** A baseline model with two convolutional layers.
2. **CNN with Extra Layers and Dropout:** An improved model with more layers and dropout regularization.
3. **CNN with Five Convolutional Layers:** A deeper model designed to capture more intricate patterns.

## Performance Metrics
The models were evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The second model, which included extra layers and dropout, achieved the highest accuracy of 91%.

## Tools and Libraries
- **PyTorch:** Framework for building and training neural networks.
- **OpenCV:** Library for image processing.
- **Matplotlib:** Library for data visualization.
- **Scikit-learn:** Library for calculating performance metrics.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cricket-shot-classification.git
   cd cricket-shot-classification
2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    
4. Run all the cells in the notebook to train the model, evaluate it, and visualize the results.

5. Review the output and results directly within the notebook.

## Future Work
- Implementing more advanced architectures like ResNet or DenseNet.
- Incorporating temporal data for video-based classification.
- Expanding the dataset with more diverse images and shot types.
- Exploring real-time shot classification for live sports analysis.

## Legal and Ethical Considerations
The project considers the legal and ethical implications of using image data for sports analytics, including intellectual property rights, player consent, and fairness in model evaluation.
