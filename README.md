# Improved-kNN

An Enhanced Version of the Classic k-Nearest Neighbors Algorithm

## 🔍 Overview

**Improved kNN** is an advanced classification algorithm that builds upon the traditional k-Nearest Neighbors (kNN) approach. This enhanced model integrates additional cluster-based intelligence such as:
- Cluster centroids
- Cluster spread
- Number of elements per cluster
- Intra-cluster distance distribution
- Distance from each point to its cluster center

These improvements enable more accurate and robust classification results across various datasets.

---

## 📊 Key Features

- 📈 Higher accuracy than standard kNN in many scenarios
- 🧠 Uses K-Means clustering to enrich training data
- 📉 Reduced misclassification in overlapping classes
- 📦 Easily extendable and adaptable to your dataset

---

## 🧪 Notebooks Included

The project contains the following Jupyter notebooks:

- `Dataset_Preparation_for_Improved_k-NN.ipynb`: Prepares and formats the dataset for training
- `Labeling_Data_with_k-Means.ipynb`: Labels data based on K-Means clusters
- `Improved_kNN.ipynb`: Main implementation of the improved algorithm
- `create_data.ipynb`: Generates synthetic datasets for experimentation

---

## 📁 Folder Structure

```
Improved-kNN/
│
├── Improved  k-NN/
│   ├── data/
│   │   ├── clustered_dataset.csv
│   │   ├── train_set.csv
│   │   └── ...
│   ├── Improved_kNN.ipynb
│   ├── Labeling_Data_with_k-Means.ipynb
│   └── ...
├── LICENSE
└── README.md
```

---

## 📷 Visual Results

Standard kNN vs Improved kNN:

| Standard kNN | Improved kNN |
|--------------|--------------|
| ![kNN](https://github.com/user-attachments/assets/0e9fb886-8fa1-4a4c-ab08-719db0b56083) | ![Improved](https://github.com/user-attachments/assets/5c9498bb-8992-4705-8989-c1a4d4b21f96) |

Additional Visualizations:

![6](https://github.com/user-attachments/assets/9b7860d1-e5a9-4404-81e4-da6e3699bb94)
![7](https://github.com/user-attachments/assets/639b27b6-4f5a-41ae-910d-aae305e921ee)
![8](https://github.com/user-attachments/assets/3d201df8-f2ed-40d4-8d7a-95b137195277)
![11](https://github.com/user-attachments/assets/4948137c-5c13-443c-b6ee-b7854fd48d8f)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Improved-kNN.git
   cd Improved-kNN
   ```

2. Open the Jupyter Notebooks in the `Improved  k-NN` folder:
   ```bash
   jupyter notebook
   ```

3. Run the notebooks in the following order:
   - `create_data.ipynb`
   - `Dataset_Preparation_for_Improved_k-NN.ipynb`
   - `Labeling_Data_with_k-Means.ipynb`
   - `Improved_kNN.ipynb`

---

## 📄 License

This project is licensed under the terms of the [MIT License](./LICENSE).

---

## 🤝 Contributions

Feel free to fork, open issues or submit pull requests. Contributions are welcome!
