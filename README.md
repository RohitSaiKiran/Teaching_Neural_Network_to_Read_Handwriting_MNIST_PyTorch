# Teaching a Neural Network to Read Handwriting — MNIST Digit Classifier in PyTorch

This project demonstrates how a **neural network can learn to read handwritten digits** using the **MNIST dataset**.  
It showcases the **end-to-end deep learning workflow** with PyTorch — from dataset preparation and model building to training, evaluation, and visualization.  
The notebook is structured to make the process **clear, professional, and reproducible**, while highlighting results and insights from the experiment.

---

## 📌 Why This Project

Handwritten digit recognition is one of the most well-known problems in computer vision and deep learning.  
Rather than simply showing code snippets, this project is designed as a **comprehensive, structured implementation** that demonstrates:

- Loading and preprocessing the MNIST dataset with PyTorch.
- Building a **fully connected neural network** from scratch.
- Training with gradient descent and monitoring the **loss curve**.
- Evaluating accuracy on unseen test data.
- Visualizing real predictions alongside their true labels.

👉 This makes it not just a coding exercise, but a **professional workflow reference** for applied deep learning.

---

## ✨ Highlights

- Hands-on exploration of **deep learning fundamentals** with PyTorch.
- Achieves **~97.6% accuracy** on MNIST after 5 epochs.
- Clear visualizations: loss curve + sample predictions.
- Organized notebook for step-by-step understanding.
- Clean, reproducible code that runs seamlessly with `torchvision.datasets`.

---

## 📖 Contents

- **Section 1**: Importing dependencies.
- **Section 2**: Loading & preprocessing the MNIST dataset.
- **Section 3**: Defining the neural network architecture.
- **Section 4**: Compiling the model (loss & optimizer).
- **Section 5**: Training loop and loss tracking.
- **Section 6**: Visualizing the training loss curve.
- **Section 7**: Evaluating model accuracy on test data.
- **Section 8**: Predictions on unseen handwritten digits.
- **Section 9**: Results & insights with improvement suggestions.

---

## 🛠️ Technologies Used

- **Libraries**: PyTorch, Torchvision, Matplotlib
- **Editor/IDE**: Jupyter Notebook / VS Code
- **Domain**: Deep Learning, Computer Vision, Image Classification
- **Dataset**: MNIST (60,000 training + 10,000 test images, 28×28 grayscale, 10 classes)

---

## 📂 Repository Structure

```
Teaching_Neural_Network_to_Read_Handwriting_MNIST_PyTorch/
│── LICENSE
│── README.md
│── requirements.txt
│
├── Notebooks/
│   └── Teaching_Neural_Network_to_Read_Handwriting_MNIST_PyTorch.ipynb
```

---

## ✅ How to Run

Clone the repository:

```bash
git clone https://github.com/RohitSaiKiran/Teaching_Neural_Network_to_Read_Handwriting_MNIST_PyTorch
```

Create a virtual environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook Notebooks/Teaching_Neural_Network_to_Read_Handwriting_MNIST_PyTorch.ipynb
```

---

## 👀 Results

- Training loss decreased smoothly from **0.34 → 0.05** over 5 epochs.
- Test accuracy reached **97.6%**, demonstrating strong generalization.
- Sample predictions were mostly correct, with occasional confusions (e.g., **5 vs 6**).

---

## 👤 Author

**Rohit Sai Kiran Ravula**  
📧 rohitsaikiran.r@gmail.com  
🔗 [GitHub Profile](https://github.com/RohitSaiKiran)

---
