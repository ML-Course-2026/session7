## **Big Picture: From Data to Deep Learning**

* We started with **datasets** as the foundation of all machine learning.
* In **Supervised Learning**, we learned from labeled data:
  * **Classification** --> predict categories (e.g., spam / not spam)
  * **Regression** --> predict continuous values (e.g., price prediction)
* **Classical Machine Learning**
  * Feature engineering + traditional models (e.g., decision trees)
* **Neural Networks**
  * **Artificial Neuron --> Multi-Layer Perceptron (MLP)**
* **Deep Learning**
  * Scales neural networks to many layers
  * Two key directions:
    * **LLMs (Transformers)** --> sequence + language understanding
      * [Demo](https://github.com/rasbt/LLMs-from-scratch/tree/main/ch05#llm-architectures-from-scratch)
    * **CNNs (Convolutional Neural Networks)** --> spatial + image data (today’s topic)
* **simple visual version**

    ```
    Datasets
    ↓
    Supervised Learning
    (Classification | Regression)
    ↓
    Classical Machine Learning
    (Trees, etc.)
    ↓
    Neural Networks
    (Artificial Neuron --> MLP)
    ↓
    Deep Learning
    ├── Transformers (LLMs)
    └── CNNs (Images) ← Today
    ```