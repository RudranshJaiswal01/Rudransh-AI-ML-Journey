# Multilayer Perceptron (MLP) from Scratch

This project demonstrates an implementation of a **Multilayer Perceptron (MLP) from scratch** using Python. The goal is to gain a deeper understanding of neural networks by manually implementing forward propagation, backpropagation, and gradient descent.

## 📂 Project Structure

- `mlp_scratch.ipynb` - Google Colab notebook implementing an MLP step by step.

## 📚 Concepts Covered

- Artificial Neural Networks (ANNs)
- Forward Propagation
- Backpropagation Algorithm
- Activation Functions (ReLU, SoftMax, etc.)
- Cross-Entropy Loss Function
- Stochastic Gradient Descent (SGD) Optimization

## 🏗 Model Details

- **Dataset**: `load_wine` from `sklearn.datasets`
- **Preprocessing**: `StandardScaler` for feature scaling
- **Model Architecture**:
  - Custom `mlp` class with flexible hidden layer sizes
  - Uses **random weight initialization** with `torch.randn`
  - Weights and biases are stored in lists and updated manually

## 📦 Libraries Used

- **Torch** - Used for tensor operations and autograd functionality.
- **Scikit-Learn** - Used for dataset loading, splitting, and preprocessing.

## 📜 Usage

You can open and run the notebook directly in **Google Colab** using the following link:

[Open in Colab](https://colab.research.google.com/drive/1ci4M2Sin8pYfE2CkBdey3r-A8KZO7KlD?usp=sharing)

**Or**

1. Upload `mlp_scratch.ipynb` to your Google Drive and open it in Colab.
2. Execute the cells step by step to follow the implementation.

## 📊 Results & Insights

- Implemented an MLP without external ML libraries.
- Used manual backpropagation and SGD for weight updates.
- Explored different activation functions and their impact on training.
- Applied model to the **Wine dataset** for classification.

## 🔮 Future Improvements

- Implement mini-batch and momentum-based optimisation techniques.
- Add support for adaptive learning rates (e.g., Adam, RMSprop).
- Experiment with deeper architectures and different activation functions.

## 📜 License

This project is for educational purposes. Feel free to use and modify the code.

---

This is a part of my AI & ML journey where I focus on implementing models from scratch to gain a better understanding of neural networks. 🚀

