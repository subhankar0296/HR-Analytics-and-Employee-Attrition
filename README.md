# 📊 Predictive HR Analytics: Employee Attrition Pipeline

An end-to-end data analytics and statistical profiling model engineered to evaluate workforce retention dynamics and organizational attrition risks. This project uses an interactive Jupyter Notebook (`python_core_fundamentals.ipynb`) to analyze operational risk indicators across 14,999 enterprise employee profiles.

---

## 📋 Data Dictionary & Attribute Specifications

The dataset tracks 10 core organizational and demographic metrics for each employee profile:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **`satisfactoryLevel`** | `float64` | Employee self-reported job satisfaction score (scaled from 0.0 to 1.0). |
| **`lastEvaluation`** | `float64` | Performance score from the employee's most recent corporate evaluation (0.0 to 1.0). |
| **`numberOfProjects`** | `int64` | The total number of distinct work projects assigned to the employee. |
| **`avgMonthlyHours`** | `int64` | The average number of operational hours worked by the employee per month. |
| **`timeSpent.company`** | `int64` | Total tenure/years the employee has spent at the company. |
| **`workAccident`** | `int64` | Binary indicator of an on-the-job incident (`0` = No accident, `1` = Accident occurred). |
| **`left`** | `int64` | **Target Variable:** Attrition status indicator (`0` = Currently Retained, `1` = Left Company). |
| **`promotionInLast5years`** | `int64` | Binary indicator of recent advancement (`0` = No promotion, `1` = Promoted). |
| **`dept`** | `object` | The corporate department assignment (e.g., Sales, Technical, Support, IT). |
| **`salary`** | `object` | Categorical compensation bracket classification (`low`, `medium`, `high`). |

---

## 🛠️ Data Science Tech Stack

* **NumPy:** Managed underlying vectorized mathematical arrays and random seed initializations.
* **Pandas:** Applied for loading matrix structures, auditing operational shapes, missing value data checks, and categorical value-count sorting.
* **Matplotlib & Seaborn:** Executed to build presentation-grade graphics, generating structural workforce proportion distributions (Pie Charts) and cross-variable attrition frequency trends (Countplots).

---

## 🗺️ Analytical Pipeline Phases

The interactive notebook executes sequentially through the following structural data checkpoints:
1. **Environment Setup:** Initializing plot styles, grid configurations, and importing the data stack.
2. **Matrix Acquisition:** Parsing the raw 14,999 rows of customer data safely using a reproducible relative file directory (`people.csv`).
3. **Feature Inspections:** Auditing data shapes, column properties, indices, and schema layouts.
4. **Volume Frequency Mapping:** Extracting categorical counts to isolate total staff weight distribution across corporate sectors.
5. **Statistical Visualization:** Deploying custom data graphics to examine employee allocations and cross-tabulate project workloads against attrition parameters (`left`).

---

## 🚀 Local Installation & Execution

### Option 1: Inline Repository View
Simply click on the `python_core_fundamentals.ipynb` file on this profile page. GitHub natively translates internal code fields and charts, allowing you to examine runtime results inside your browser window without running any code.

### Option 2: Running Environment Packages Locally
To execute the interactive notebook cells on your local machine:

1. **Clone the assets repository:**
   ```bash
   git clone https://github.com/subhankar0296/HR-Analytics-and-Employee-Attrition.git
