

# **Customer Segmentation and Lookalike Model - Data Science Assignment**

## **Overview**
This project focuses on analyzing an eCommerce dataset to derive insights, build predictive models, and perform customer segmentation. The main objectives include:
1. Performing **Exploratory Data Analysis (EDA)**.
2. Building a **Lookalike Model** to recommend similar customers.
3. Performing **Customer Segmentation** using clustering techniques.

---

## **Project Structure**
```
├── Customers.csv           # Customer data
├── Products.csv            # Product data
├── Transactions.csv        # Transaction data
├── FirstName_LastName_EDA.ipynb       # Jupyter Notebook for EDA
├── FirstName_LastName_EDA.pdf         # PDF report for EDA insights
├── FirstName_LastName_Lookalike.ipynb # Jupyter Notebook for Lookalike Model
├── FirstName_LastName_Lookalike.csv   # CSV output with top 3 similar customers
├── FirstName_LastName_Clustering.ipynb # Jupyter Notebook for clustering
├── Customer_Segments.csv   # Cluster assignment results
├── README.md               # Project documentation
```

---

## **Tasks and Deliverables**

### **Task 1: Exploratory Data Analysis (EDA)**
- **Objective**: Analyze the dataset to uncover trends and derive at least 5 business insights.
- **Deliverables**:
  - `FirstName_LastName_EDA.ipynb`: Contains EDA code and visualizations.
  - `FirstName_LastName_EDA.pdf`: Summarized insights in PDF format.

---

### **Task 2: Lookalike Model**
- **Objective**: Build a model to recommend the top 3 similar customers based on transaction and profile data.
- **Deliverables**:
  - `FirstName_LastName_Lookalike.ipynb`: Model code implementation.
  - `FirstName_LastName_Lookalike.csv`: Output file with the top 3 recommendations for the first 20 customers in the format:
    ```
    CustomerID,SimilarCustomers
    C0001,"[(C0004, 0.98), (C0003, 0.95), (C0002, 0.93)]"
    ```

---

### **Task 3: Customer Segmentation**
- **Objective**: Perform clustering to group customers based on their profile and transaction history.
- **Metrics**:
  - **Davies-Bouldin Index (DBI)** to evaluate cluster quality.
- **Deliverables**:
  - `FirstName_LastName_Clustering.ipynb`: Clustering implementation with visualizations.
  - `Customer_Segments.csv`: CSV file with customer cluster assignments.
  - Visualizations:
    - DBI vs. number of clusters.
    - PCA and t-SNE scatterplots for cluster visualization.

---

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/YourRepositoryName.git
   cd YourRepositoryName
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute the notebooks in the following order:
   - `FirstName_LastName_EDA.ipynb`
   - `FirstName_LastName_Lookalike.ipynb`
   - `FirstName_LastName_Clustering.ipynb`

---

## **Insights and Results**
1. **EDA**:
   - Highlighted key trends in customer demographics, product categories, and revenue patterns.
   - Insights are available in the PDF report.

2. **Lookalike Model**:
   - Recommended top 3 similar customers with similarity scores for the first 20 customers.

3. **Clustering**:
   - Identified distinct customer groups using KMeans clustering.
   - Achieved optimal clusters with the lowest DBI value.

---

## **License**
This project is for educational purposes only. Data provided in the assignment remains the property of its respective owner.

---

Feel free to customize the repository name, username, and additional sections as needed. Let me know if you need help with a `requirements.txt` file or other setup instructions!
