## 🧠 Implemented Models

This project implements several fundamental machine learning models **from scratch using JAX** to better understand their internal mechanics and training dynamics.

The following models were implemented without relying on high-level ML frameworks:

1. **Linear Regression**  
   A basic regression model trained using gradient descent to predict continuous values.

2. **Logistic Regression**  
   A probabilistic classification model using the sigmoid function for binary outcomes.

3. **MLP for Regression**  
   A Multi-Layer Perceptron designed to learn non-linear relationships in regression tasks.

4. **MLP for Binary Classification**  
   A neural network model used for binary classification with hidden layers and sigmoid output.

---

## ⚙️ Model Implementation

All models include manual implementations of:

- Forward propagation
- Loss functions
- Gradient computation
- Parameter updates
- Training loops

This approach provides deeper insight into how machine learning algorithms learn from data.

---

## 📊 Framework Comparison

To validate correctness and performance, the custom implementations were compared with industry-standard libraries:

- **Scikit-learn**
- **TensorFlow**

The comparison helped verify:

- Model accuracy
- Training behavior
- Performance differences
- Implementation correctness

---

## 🎯 Goal

The main objective of this project is to understand the **mathematical foundations and internal workings of machine learning models** by implementing them from scratch rather than relying entirely on high-level APIs.

This helps build stronger intuition for:

- Gradient-based optimization
- Neural network training
- Model behavior and limitations
