# 🌌 Applications of Physics-Informed Machine Learning

Welcome to my **Physics-Informed Machine Learning** repository, created during my research at the University of Washington! This collection of notebooks combines machine learning with physical laws to solve complex scientific and engineering problems, especially when data is sparse or noisy. By embedding physics directly into the learning process, PIML models achieve accurate, interpretable solutions that respect fundamental principles of physics. 🌍💡

## 📂 Contents

1. **[Burgers-Discovery with a Single Dataset.ipynb](https://github.com/MunzirH/Applications-of-Physics-Informed-Machine-Learning/blob/main/Burgers-Discovery%20with%20a%20single%20dataset-.ipynb)**:
   - **Purpose**: Applies PIML to discover the **Burgers equation**—a fundamental PDE in fluid dynamics—using sparse data.
   - **Highlights**:
     - Uses **Physics-Informed Neural Networks (PINNs)** to model Burgers dynamics.
     - Focuses on extracting accurate insights even from limited data by embedding physical constraints into the neural network.
     - Provides a step-by-step guide for setting up a PINN to learn the underlying physics of the Burgers system, with visualizations comparing model predictions to actual dynamics.

2. **[Experimental Data.ipynb](https://github.com/MunzirH/Applications-of-Physics-Informed-Machine-Learning/blob/main/Experimental%20data.ipynb)**:
   - **Purpose**: Preprocesses and analyzes experimental data to prepare it for physics-informed modeling.
   - **Highlights**:
     - Cleans, normalizes, and prepares data from physical experiments, making it ideal for training PINNs and other PIML models.
     - Demonstrates handling challenges like noise and sparsity in real-world data, ensuring the data is ready for accurate model training.
     - Visualizes the data structure and insights, setting the stage for reliable physics-informed modeling.

3. **[Part 1, 2 - SINDy: ODEINT.ipynb](https://github.com/MunzirH/Applications-of-Physics-Informed-Machine-Learning/blob/main/Part%201%2C2%20-%20SINDy%3AODEINT.ipynb)**:
   - **Purpose**: Uses **Sparse Identification of Nonlinear Dynamics (SINDy)** with **ODEINT** to uncover the governing ODEs of a dynamic system.
   - **Highlights**:
     - **SINDy** identifies sparse models that describe dynamic systems, ideal for discovering concise mathematical equations from noisy data.
     - Uses **ODEINT** solvers in Python to solve these equations, enabling comparison with known dynamics.
     - Shows a structured approach to uncovering governing equations for complex systems, isolating relevant terms and achieving interpretable results.

4. **[Part 3 - PINN.ipynb](https://github.com/MunzirH/Applications-of-Physics-Informed-Machine-Learning/blob/main/Part%203%20-%20PINN.ipynb)**:
   - **Purpose**: Explores **Physics-Informed Neural Networks (PINNs)** for solving PDEs by embedding physical constraints in the learning model.
   - **Highlights**:
     - Builds a PINN to solve a specific PDE, showing how neural networks can integrate physics constraints for physically plausible solutions.
     - Assesses PINNs for complex systems, particularly where traditional methods struggle due to sparse data or high computational costs.
     - Visualizes predictions vs. known solutions, emphasizing how PINNs respect physical laws even with limited training data.

## 🌟 Key Concepts and Highlights

- **Physics-Informed Neural Networks (PINNs)**: These neural networks incorporate physical laws, such as conservation principles or known equations, directly into the loss function. By doing so, the model respects these laws during training, achieving both accuracy and physical meaning.
- **Sparse Identification of Nonlinear Dynamics (SINDy)**: SINDy is a technique for deriving governing equations of dynamic systems from sparse and noisy data. It helps identify the simplest mathematical structure that fits the data, yielding concise and interpretable models.
- **Experimental Data Handling**: Many real-world physical systems produce sparse or noisy data, making them challenging for traditional models. This repository demonstrates preprocessing, normalizing, and visualizing experimental data, preparing it for use in machine learning models.
- **Model Discovery and Analysis**: By using machine learning to derive underlying equations, this repository bridges traditional physics and modern AI, offering new insights and solutions in scientific and engineering applications.

## 🔧 Requirements

- **Python** (version 3.x)
- **Jupyter Notebook** or **JupyterLab**
- **Scientific Computing Libraries**:
  - `numpy`, `scipy`, `matplotlib` for data manipulation and visualization.
  - `torch` or `tensorflow` for building neural networks (depending on notebook requirements).
  - **Additional Libraries**: Some notebooks may require libraries like `scikit-learn` or `SymPy` for symbolic calculations.

  - **Additional Libraries**: Some notebooks may require libraries like `scikit-learn` or `SymPy` for symbolic calculations.
