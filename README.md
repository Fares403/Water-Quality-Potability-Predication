# Water Potability Prediction 

## Overview  
This project predicts whether water is **potable** (safe for drinking) or not based on its physicochemical properties. Using machine learning, we analyze features like pH, hardness, solids, and others to classify water samples.  

---

## Dataset  
The dataset contains the following features:  
- `ph`: Acidity/alkalinity level of water.  
- `Hardness`: Calcium and magnesium concentration in water.  
- `Solids`: Total dissolved solids in ppm.  
- `Chloramines`: Chlorine-based disinfectant concentration.  
- `Sulfate`: Sulfate ion concentration.  
- `Conductivity`: Electrical conductivity of water.  
- `Organic_carbon`: Organic carbon content in water.  
- `Trihalomethanes`: Trihalomethane concentration (chlorine byproducts).  
- `Turbidity`: Cloudiness or haziness of water.  
- `Potability`: Target variable (1 = Potable, 0 = Not potable).  

---

## Model  
The **Extra Trees Classifier** was used as the final model.  

**Results**:  
- **Accuracy**: 71.57%  
- **Precision**: 70.38% (class 0), 72.92% (class 1)  
- **Recall**: 74.60% (class 0), 68.54% (class 1)  
- **F1-Score**: 72.43% (class 0), 70.66% (class 1)  
---

## Future Improvements  
- Explore advanced models or ensembles.  
- Optimize feature engineering for better performance.  
- Deploy the model as a web app.  

---

Feel free to use or improve this project! 
