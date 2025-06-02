# 🛡️ Cybersecurity Threat Detection using Machine Learning

This project is built to help identify suspicious or harmful web traffic. It uses machine learning techniques to detect patterns that could point to hacking, attacks, or unsafe network behavior.

---

### ✅ What the Project Does

This notebook does several things step by step:

- 📂 **Loads and cleans the traffic data** to remove any duplicates or errors.
- 🧠 **Creates useful new features** like:
  - `duration`: How long a connection lasted
  - `packet_size`: How much data was sent per second
- 🚨 **Checks if an IP address is blacklisted** (known for suspicious activity).
- 🔎 **Detects unusual traffic** using an unsupervised machine learning method called **Isolation Forest**.
- 🤖 **Trains two different models**:
  - A **Random Forest classifier**
  - A simple **Neural Network**
- 📊 **Evaluates the models** using accuracy and other performance metrics.

---

### 📁 What's Included

- `cybersecurity.ipynb`: The main Jupyter Notebook containing the full code and analysis
- `CloudWatch_Traffic_Web_Attack.csv`: The dataset used (if not public, you can mention how to get it)

---

### 🚀 How to Use This Project

To run this notebook:

 1. ✅ Make sure you have [Jupyter Notebook](https://jupyter.org/) or JupyterLab installed. 
 2. ✅ Install the required Python libraries if you don’t already have them:
 3. ✅ Open `cybersecurity.ipynb` in Jupyter.
 4. ✅ Run the notebook **cell by cell** from top to bottom.

---

### 💡 Why This Project Matters

With the rise in web attacks and harmful bots, identifying suspicious traffic has become very important. This project provides a simple and powerful way to start building automated detection systems for cybersecurity.

---

### 🙋‍♂️ Feel free to fork, improve, or share!

You can use this project as a base for your own experiments in anomaly detection or security analysis. Pull requests are welcome!


