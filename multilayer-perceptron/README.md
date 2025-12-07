## Neural Network Experiments for Song Year Prediction

***

This repository details a deep learning project dedicated to predicting the **release year of a song** based on its intrinsic audio features, utilizing the **Million Songs Dataset**.

### **Objective**

The core objective was to conduct an **experimental analysis** of various design choices within a **Fully Connected Neural Network (FCNN)** to optimize performance for this multi-class classification challenge.

### **Experiments and Focus Areas**

* **Architecture Tuning**: Focus was placed on experimenting with the **depth** (number of layers) of the FCNN, along with the strategic implementation of **Dropout** layers for effective regularization.
* **Optimization Comparison**: Different **optimization algorithms** (SGD+momentum и Adam) were tested and compared to assess their influence on the network's **convergence speed** and final **prediction accuracy**.

### **Technical Summary**

* **Framework**: The model was built and trained using a leading **deep learning framework** (PyTorch).
* **Dataset**: **Million Songs Dataset**.
* **Metric**: The model was optimized using the **Cross-Entropy Loss** function.
* **Tools**: Standard **scientific computing libraries** (NumPy, Pandas), **data visualization tools** (Matplotlib, Seaborn), and tools for efficient iteration and display (Jupyter/IPython) were used for implementation and analysis.
