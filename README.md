# **Assessing Global Development Needs: A Data Driven Approach for Strategic Aid Allocation**
This project leverages unsupervised machine learning techniques to categorize countries based on critical socio-economic and health factors such as child mortality, exports, health, imports, income, inflation, life expectancy, total fertility rate, and GDP per capita that influence their overall development. By analyzing the dataset, we aim to identify patterns and group countries into categories reflecting their need for assistance. The findings will enable HELP International to strategically allocate $10 million in aid to the countries that require it the most, optimizing resource distribution and maximizing impact in alleviating poverty and improving living conditions.

### **Exploratory Data Analysis (EDA):**
* Conducted EDA to understand data distributions, correlations, and patterns.
* Visualized key metrics using plots (histograms, boxplots, scatter plots) to identify trends and anomalies.
* Documented insights and initial findings to guide further analysis.

### **Data Preprocessing:**
* **Outlier Handling:** Identified and capped the outliers to minimize their impact on the analysis.
* **Data Scaling:** Standardized the data using Standard scaling.
  
### **Dimensionality Reduction:**
* Applied Principal Component Analysis (PCA) to reduce the dataset's dimensionality.
* Selected the number of principal components that explained 95% of the variance (finalized 5 PCs).

### **Clustering Analysis:**
**KMeans Clustering**
* Determined the optimal number of clusters (k=3) using methods such as the elbow method and silhouette score analysis.
* Performed KMeans clustering to categorize countries into three distinct clusters based on the selected principal components.
  **Agglomerative Clustering**
* Conducted agglomerative clustering for comparison and validation of clustering results.
* Analyzed the cluster formation and consistency across both methods.

**Cluster Interpretation:**
Analyzed the characteristics of each identified cluster:
* **Cluster 0(Developed):**  High-income countries with advanced socio-economic indicators (e.g., high income, low child mortality, high life expectancy).
* **Cluster 1(Under-Developed):**  Low-income countries facing significant challenges (e.g., low income, high child mortality, high fertility rates).
* **Cluster 2(Developing):**  Middle-income countries with moderate socio-economic conditions (e.g., balanced income levels, moderate mortality and fertility rates).

**Key Insights for Business and Policy:**
* **Targeted Investments:** The classification helps businesses and governments identify which countries may need more investment in infrastructure, healthcare, and education to improve their economic standing.
* **Policy Recommendations:** For developing and underdeveloped countries, there is a need for policies focused on reducing child mortality and improving healthcare, which will drive long-term economic growth.
* **Trade and Investment Opportunities:** Developed countries can be targeted for high-value goods and services, while developing countries may offer opportunities in emerging markets, and underdeveloped   
    countries may present opportunities for development aid and infrastructure projects.
  
This interpretation provides actionable insights for economic development strategies, international trade, and investment decision-making.
