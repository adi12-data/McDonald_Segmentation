# 🍔 McDonald's Customer Segmentation Analysis

This project performs market segmentation on McDonald's customer data using unsupervised machine learning techniques. The goal is to identify distinct customer segments based on their demographics and preferences to support data-driven marketing strategies.

## 📊 Techniques Used

- **K-Means Clustering** (k=4)
- **Gaussian Mixture Model (GMM)**
- **Cross-tabulation Analysis**
- **Mosaic Plot for Cluster-Attribute Relationships**
- **Decision Tree Classification to Explain Cluster Membership**
- **Segment Profiling Visualization**

## 🔍 Dataset Info

The dataset includes anonymized survey responses with the following features:
- Age
- Gender
- Visit Frequency
- Like Score (opinions about McDonald's)
- Other binary/categorical variables

## 🧠 Key Insights

- Cluster analysis reveals 4 distinct customer segments.
- GMM and K-Means segmentation overlap significantly.
- Mosaic plots highlight how clusters relate to customer sentiment.
- Decision trees help understand what features lead to membership in each cluster.
- Segment profiles (Visit frequency vs. Like score) offer a visual summary, with marker size representing the proportion of females.

## 📁 Files

- `McDonald.ipynb`: Main notebook with full analysis
- `data/`: Folder for data
- `README.md`: Project overview

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/adi12-data/McDonald_Segmentation.git
   cd McDonald_Segmentation
2. Create and activate virtual environment:

    bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows

3. Install dependencies:

    bash
    pip install -r requirements.txt

🚀 Usage
Launch Jupyter Notebook:

jupyter notebook McDonald.ipynb

Run cells sequentially to:

Load and preprocess data
Perform PCA analysis
Apply clustering algorithms
Generate visualizations
Interpret results

## 🤝 Contributing

Feel free to open issues or submit pull requests for improvements or new features.
---

## 📃 License

[MIT License](LICENSE)
---

## 👤 Author
Created by [Aditya Khandelwal] — [khandelwaladi123@gmail.com](mailto:khandelwaladi123@gmail.com)
