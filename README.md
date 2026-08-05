
# Ambulance Position for Road Accidents

## 🚑 Project Overview
This project aims to optimize ambulance deployment strategies to minimize response times to road accidents. By leveraging machine learning techniques like clustering, this project analyzes accident data to determine the most optimal locations for ambulance deployment.

The solution is based on accident datasets from Nairobi, focusing on both static and dynamic ambulance placement using methods like **K-Means clustering**.

---

## 📊 Dataset
- **Train Dataset**: Historical accident data with latitude, longitude, and timestamps.
- **Test Dataset**: Accident timestamps without location data for validation.

---

## 📈 Key Features
1. **Static Ambulance Placement**: 
   - Uses K-Means clustering to find fixed locations for ambulances based on historical crash data.

2. **Dynamic Ambulance Placement**:
   - Groups crashes by time intervals (e.g., every 3 hours) and applies K-Means clustering to adjust ambulance positions dynamically.

3. **Comparison of Models**:
   - Compares the performance of static and dynamic placement strategies.

4. **Visualization**:
   - Scatter plots to visualize crash locations and ambulance placements.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `swifter`, `bayesian-optimization`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Satwika-reddi/Ambulance-position-for-road-accidents.git
   cd Ambulance-position-for-road-accidents
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧑‍💻 Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Ambulance position for road accidents.ipynb"
   ```
2. Run through the cells to:
   - Load and preprocess the dataset.
   - Visualize accident data.
   - Perform static and dynamic clustering.
   - Generate submission files for evaluation.

---

## 📂 Project Structure
- **`Ambulance position for road accidents.ipynb`**: Main notebook containing all code and analysis.
- **`Train.csv`**: Training dataset with accident locations and timestamps.
- **`SampleSubmission.csv`**: Submission format for output files.
- **`kmeans.csv`**: Output of the static ambulance placement model.
- **`kmeans_by_time.csv`**: Output of the dynamic placement model.

---

## 📖 Results
- **Static Placement**: Fixed ambulance locations using K-Means clustering.
- **Dynamic Placement**: Time-based clustering to optimize ambulance positions dynamically.
- **Comparison**: Demonstrates the effectiveness of time-based models in reducing response times.

---

## 🎯 Future Enhancements
- Integration with real-time accident data.
- Incorporation of road conditions and traffic data.
- Deployment of the model in production systems.

---

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or suggestions.


---

## 🙌 Acknowledgments
- **Dataset**: Historical crash data from Nairobi.
- **Libraries Used**: scikit-learn, matplotlib, pandas, etc.

---

Would you like me to help you update the `README.md` file directly in your repository?
  
