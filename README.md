## 🫁 Lung Cancer Tissue Classification using Random Forest Classifier

### 📌 Project Overview
This project utilizes **Random Forest Classifier** algorithm to differentiate **tumor (T)** and adjacent **adjacent non-tumor tissues (NT)**  lung cancer tissues based on  **lipidomics** data derived from tissue extracts of lung cancer patients.

### 📂 Dataset Information
- 📁 **File name**:`Primary LC dataset.xlsx`, `Entire dataset.xlsx`
- 🎯 **Target Variable**: `Group` (`NT` = 0, `T` = 1)
- 📄 **Features**: `m/z`
    - *Each feature represents a lipid intensity from LC/MS<sup>E</sup> analysis*
      
### 🧹 Data Preprocessing 
- 🔄 **Normalization**: `MinMaxScaler`

### 🤖 Model Training: Random Forest Classifier
- 🛠️ **Hyperparameters for Primary LC dataset**:
   - `n_estimators = 500`
   - `max_features = sqrt`
   - `max_depth = 4`
   - `min_samples_split = 10`
   - `min_samples_leaf = 4`
   - `oob_score = True`
   - `random_state = 42`

- 🛠️ **Hyperparameters for Entire dataset**:
   - `n_estimators = 500`
   - `max_features = None`
   - `max_depth = 4`
   - `min_samples_split = 2`
   - `min_samples_leaf = 4`
   - `oob_score = True`
   - `random_state = 42`
    
