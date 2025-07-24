# Diwali Sales Analysis Project

This project analyzes Diwali sales data using Python and visualizations. It provides insights into customer demographics, product categories, and purchasing trends.

## Dataset
- **Diwali Sales Data.csv**: Contains customer, product, and sales details for Diwali purchases.

## Prerequisites
- Python 3.7 or higher
- Recommended: Use a virtual environment (venv or conda)

## Supported Platforms
- Visual Studio Code (VS Code)
- Google Colab

---

## Installation & Running on VS Code

1. **Clone or Download the Repository**
   - Download the project folder or clone using:
     ```bash
     git clone <repo-url>
     ```

2. **Navigate to the Project Directory**
   ```bash
   cd "Python_Diwali_Sales_Analysis-main"
   ```

3. **Create and Activate a Virtual Environment (Optional but Recommended)**
   - Using `venv`:
     ```bash
     python -m venv venv
     source venv/Scripts/activate  # On Windows
     ```
   - Or using `conda`:
     ```bash
     conda create -n diwali_env python=3.8
     conda activate diwali_env
     ```

4. **Install Required Python Packages**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

5. **(VS Code Only) Install Jupyter Extension**
   - Open VS Code and install the official Jupyter extension from the Extensions Marketplace.

6. **Open and Run the Notebook**
   - Open `Diwali_sales_project.ipynb` in VS Code.
   - Run each cell step-by-step to:
     - Import libraries
     - Load and inspect the dataset
     - Perform data cleaning and feature engineering
     - Visualize sales and demographic trends
     - Generate insights and conclusions

---

## Running on Google Colab

1. **Upload Files to Colab**
   - Go to [Google Colab](https://colab.research.google.com/).
   - Upload `Diwali_sales_project.ipynb` and `Diwali Sales Data.csv` to your Colab environment.

2. **Install Required Packages (if needed)**
   - Colab comes with most packages pre-installed. If needed, run:
     ```python
     !pip install pandas numpy matplotlib seaborn
     ```

3. **Run the Notebook**
   - Open `Diwali_sales_project.ipynb` in Colab.
   - Run each cell in order as described above.

---

## Example Commands
```python
import pandas as pd
df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')
```
---