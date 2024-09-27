# Bank Customer Evaluation
!['Bank Customer Segmentation'](https://www.aimtechnologies.co/wp-content/uploads/2023/08/Customer-Segmentation-Analysis.jpg)

**Use Case**:  
The goal is to develop a machine learning model from scratch, including all steps from data exploration to deployment. The process should include detailed commentary at each stage, not just Python scripts, with a special focus on insights and evaluations at each step. The dataset’s target variable is **"Bought"** (dependent variable).

## Process Overview:

### 1. Data Analyst Perspective:
   - **Data Exploration**: Perform a comprehensive analysis of the dataset to understand its structure and identify any patterns or anomalies.
   - **Report Preparation**: Create a report summarizing the key insights from the data, including visualizations and statistics.
   - **Hypothesis Generation**: Propose possible insights and assumptions based on the data analysis (e.g., patterns or trends related to customer behavior).

### 2. Data Scientist Perspective:
   - **Feature Engineering**: Process and create new features to enhance model performance.
   - **Imbalance Handling**: Address any class imbalance issues to ensure fair model training.
   - **Model Creation**: Develop and train the machine learning model using the prepared data.
   - **Model Class Creation**: Build a class-based system for the model to improve modularity and reusability.
   - **Model Development**: Fine-tune the model, evaluate performance metrics, and document the results.

---

## Bank Customer Evaluation App:

**Features**:
- **Customer ID**: Entered as input (does not affect the model but is important for customer classification).
- **Customer Gender**: Impacts the model; can be evaluated using feature importance analysis.
- **Number of Customer Transactions**: Counts customer activities.
- **Average Days Between ATM Transactions**: Measures the frequency of ATM usage.
- **Current Customer Balance**: Indicates the current financial status.
- **Median of Cash Transactions**: Reflects the typical cash transaction behavior.
- **Customer Phone Type**: Helps in segmentation but can be explored further for model impact.
- **Model Output**: Provides the predicted classification of whether the customer will make a purchase or not.

## Link to App:
Explore the model [here](https://huggingface.co/spaces/riyadahmadov/Bank_Customer_Estimated).
