# Power BI Report: Insurance Dataset Analysis

## Overview
Power BI report analyzing an insurance dataset that includes information on insurance charges based on attributes such as **Age**, **Sex**, **BMI**, **Number of Children**, **Smoker Status**, and **Region**. The report provides interactive visualizations and insights to help explore key trends and relationships in the data.

---

## Dataset Description
The dataset consists of the following attributes:
- **Age**: Age of the insured.
- **Sex**: Gender (Male/Female).
- **BMI**: Body Mass Index (Numerical).
- **Number of Children**: Number of Children Customers have.
- **Smoker**: Smoking status (Yes/No).
- **Region**: Residential area of the insured (Northeast, Northwest, Southeast, Southwest).
- **Insurance Charges**: Premium amount charged to the insured.

---

## Report Highlights
The Power BI report includes the following features and visualizations:

### **KPI Cards**
- **Number of Customers**: Displays the total number of customers in the dataset.
- **Average Charges**: Shows the average insurance charges across all customers.

### **Tile Filters**
- **Region Filter**: Interactive filter for selecting data by region (Northeast, Northwest, Southeast, Southwest).
- **Gender Filter**: Interactive filter for selecting data by gender (Male/Female).

### **Visualizations**
1. **Stacked Column Chart: Number of Children**  
   - Displays the count of customers based on the number of children.

2. **Stacked Column Chart: Average Charges by Age Group**  
   - Compares the average insurance charges across different age groups.

3. **Pie Chart: Smoker vs. Non-Smoker**  
   - Visualizes the proportion of smokers and non-smokers in the dataset.

4. **Stacked Bar Chart: Average BMI by Gender and Smoker Status**  
   - **X-Axis**: Average BMI.  
   - **Y-Axis**: Smoker status (Smoker/Non-Smoker).  
   - **Legend**: Gender (Male/Female).

---

## How to Use
1. Download the `.pbix` file from this repository.
2. Open the file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Interact with the dashboard by:
   - Selecting regions using filters.
   - Exploring different visualizations for detailed insights.

---

## Preview
### Dashboard Overview
![Health Insurance Report Screenshot](https://github.com/user-attachments/assets/b9d7c2e0-738b-4b8b-8af8-c71d7bf6e02f)


---

## Insights
- Regions and genders can be dynamically explored to uncover regional trends in charges and smoker behavior.
- Smoker status significantly impacts average BMI and insurance charges.
- Visualizations highlight the relationships between age, BMI, and insurance charges.

---

## File Structure
- **Health Insurance Report.pbix**: Power BI report file containing all the visualizations and insights.
- This dataset can be downloaded from Kaggle: [US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset) or from the file `insurance.csv` [Data](insurance.csv).

---

## Acknowledgements
This report was created to demonstrate data analysis and visualization using Power BI.

---

## Contributions
Feel free to open an [issue](https://github.com/arjunj14/PowerBI/issues) or submit a pull request to enhance the dashboard or add new features.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE)file for details.



