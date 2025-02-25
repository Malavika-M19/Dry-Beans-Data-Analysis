# Dry-Beans-Data-Analysis  
This is a machine learning project that uses several ML models to predict\classify the dry bean variety based on several aspects of it.🌱  
Supervised learning method is implemented. The model is trained with existing data to predict the dry bean variety  

🔣The Dataset: https://archive.ics.uci.edu/dataset/602/dry+bean+dataset  
Shape: 13611X17
The features are: 
- **Area**: The area of a bean zone and the number of pixels within its boundaries.  
- **Perimeter**: Bean circumference is defined as the length of its border.  
- **Major axis length**: The distance between the ends of the longest line that can be drawn from a bean.  
- **Minor axis length**: The longest line that can be drawn from the bean while standing perpendicular to the main axis.  
- **Aspect ratio**: Defines the relationship between major and minor axis lengths.  
- **Eccentricity**: Eccentricity of the ellipse having the same moments as the region.  
- **Convex area**: Number of pixels in the smallest convex polygon that can contain the area of a bean seed.  
- **Equivalent diameter**: The diameter of a circle having the same area as a bean seed area.  
- **Extent**: The ratio of the pixels in the bounding box to the bean area.  
- **Solidity**: Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.  
- **Roundness**: Calculated with the formula (4π × Area) / (Perimeter²).  
- **Compactness**: Measures the roundness of an object using the ratio of equivalent diameter to major axis length.  
- **ShapeFactor1**  
- **ShapeFactor2**  
- **ShapeFactor3**  
- **ShapeFactor4**

**Workflow of this project:**
🛒Data Loading  
🩺Handling Skweness  
🩺Handling Outliers  
🏷Encoding Categorical values  
📎Correlation Analysis  
💡Feature Selection  
✂ Data Splitting  
📏Scaling  
⚖ Imbalance Correction  
🧱Model building  
🏁Model Evaluation  
🔬Hyperparameter tuning  
🦾Building Pipeline  
🗂Model Saving  
🔎Test with unseen data  

Meachine Learning Models Trainded: [Logistic Regression, Ridge Classification, Support Vector Machine, K-Nearest Neighbours, Gradient Booster, Random Forest]


