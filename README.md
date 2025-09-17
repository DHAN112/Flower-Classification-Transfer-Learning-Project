# 🌺 Transfer Learning for Flower Classification

This project is a submission for the "21 Projects in 21 Days" initiative by GeeksforGeeks, mentored by Ashish Jangra Sir. It demonstrates the use of transfer learning for fine-grained image classification on the Oxford Flowers 102 dataset.

---

### ## 📝 Project Overview
The goal of this project was to adapt powerful, pre-trained convolutional neural networks (CNNs) to classify 102 different species of flowers. By leveraging models already trained on the vast ImageNet dataset, we can achieve high accuracy with minimal training time.

---

### ## 🤖 Models Used
Three different pre-trained architectures were implemented and compared:
* **ResNet50**
* **VGG16**
* **MobileNetV2**

---

### ## 📈 Results
After training for 10 epochs on the frozen base models, the following accuracies were achieved on the test set:

| Model | Test Accuracy |
| :--- | :--- |
| **ResNet50** | **92.48%** |
| **VGG16** | **88.17%** |
| **MobileNetV2** | **90.35%** |

---

### ## 🚀 How to Run
1.  Open the `flower_classification_notebook.ipynb` file in Google Colab or another Jupyter environment.
2.  Ensure a **GPU runtime** is selected for efficient training.
3.  Run the cells sequentially to load the dataset, preprocess the data, build the models, train them, and evaluate the final performance.
