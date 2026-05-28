# 🏥 Medical Appointments No-Show Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a medical appointments dataset to understand the factors affecting whether patients show up for their scheduled appointments.

The analysis focuses on identifying trends and patterns related to:

* Patient demographics
* Appointment scheduling behavior
* Health conditions
* SMS reminders
* Scholarship availability
* Appointment attendance patterns

The project was completed using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** in a Jupyter Notebook environment.

---

# 📂 Dataset Information

The dataset contains details of medical appointments including:

* Patient ID
* Gender
* Age
* Appointment date
* Scheduled date
* Health conditions
* Scholarship information
* SMS reminders
* Whether the patient showed up or not

### Target Variable

* **NoShow**

  * `Yes` → Patient did not attend the appointment
  * `No` → Patient attended the appointment

---

# 🛠️ Technologies Used

* Python 🐍
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# 📊 Steps Performed in the Analysis

## 1️⃣ Data Loading

* Imported dataset using Pandas
* Checked dataset structure and dimensions

## 2️⃣ Data Cleaning

* Converted date columns into proper datetime format
* Renamed incorrect column names
* Removed unnecessary columns
* Checked for missing values

## 3️⃣ Feature Engineering

Created new features such as:

* Appointment weekday
* Schedule weekday
* Age groups

## 4️⃣ Exploratory Data Analysis (EDA)

Performed:

* Univariate analysis
* Bivariate analysis
* Correlation analysis
* Distribution analysis
* Attendance pattern analysis

## 5️⃣ Data Visualization

Generated visualizations using:

* Bar plots
* Count plots
* Heatmaps
* Correlation charts

---

# 📈 Key Insights

* Female patients booked more appointments compared to male patients.
* Most patients attended their appointments.
* SMS reminders showed limited impact on attendance.
* Scholarship patients had different attendance behavior.
* Certain age groups showed higher attendance rates.
* Hypertension and diabetes were analyzed against appointment attendance.

---

# 📷 Sample Visualizations

Some visualizations included in the project:

* No-show distribution
* Age group analysis
* Gender-wise attendance
* Correlation heatmap
* Health condition comparison

---

# 📁 Project Structure

```bash
├── Data.csv
├── Medical_Appointments_Data_EDA.ipynb
└── README.md
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/piyushpawar924-dot/medical-appointments-eda.git
```

## 2️⃣ Navigate to the Project Folder

```bash
cd medical-appointments-eda
```

## 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file:

```bash
Medical_Appointments_Data_EDA.ipynb
```
---

# 👨‍💻 Author

PIYUSH PAWAR <br>
DATA ANALYTICS ENTHUSIAST

If you like this project, give it a ⭐ on GitHub!
