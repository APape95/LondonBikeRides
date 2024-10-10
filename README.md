# London Bike Rides Analysis

This project analyses bike ride data from London, visualising key trends and insights using Tableau. The goal is to provide a comprehensive overview of bike usage patterns across different hours and locations in the city.

## 🚴‍♀️ Project Overview
The project aims to analyze bike rides across London, identifying trends in ride duration, popular start and end locations, and hourly usage patterns. Using Python for data preprocessing and Tableau for data visualization, this analysis provides insights into how bikes are used throughout the city.

## 🛠 Technologies Used
- **Python**: Data manipulation and cleaning using `pandas` and `numpy`
- **Tableau**: For interactive data visualization
- **Jupyter Notebook**: To document the data cleaning and analysis process
- **SQL**: Database querying for data extraction

## 📊 Tableau Dashboard
Explore the interactive visualizations that provide insights into bike usage across London:
[View the Tableau Dashboard here](https://public.tableau.com/views/LondonBikeRidesDashboard_17285879727540/Hour?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📁 Project Structure
```
├── data/                     # Contains the raw and processed datasets
├── notebooks/                # Jupyter notebooks for data cleaning and EDA
├── src/                      # Python scripts for data analysis
├── images/                   # Screenshots of the Tableau visualizations
├── README.md                 # Project documentation
└── requirements.txt          # Python package dependencies
```

## 💾 Dataset
The dataset used for this project includes information on bike rides in London, detailing:
- Start and end locations
- Ride durations
- Time of day
- Weather conditions

### Source
Data is sourced from [London bike sharing dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

## 🚀 Getting Started
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/APape95/LondonBikeRides.git
   cd LondonBikeRides
   ```

2. **Install dependencies:**
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis:**
   Open the Jupyter notebook in the `notebooks` folder to explore the data analysis:
   ```bash
   jupyter notebook notebooks/data_analysis.ipynb
   ```

## 🖼 Screenshots
### Example Visualization
![Tableau Dashboard Screenshot](images/tableau_dashboard_example.png)

## ✨ Key Insights
- **Peak Usage Hours**: The data revealed that bike rides peak during morning and evening rush hours.
- **Popular Routes**: Central London locations have the highest number of ride starts and ends.
- **Ride Duration Trends**: Weekends show longer ride durations compared to weekdays.

## 📬 Contact
If you have any questions or feedback, feel free to reach out:
- **GitHub**: [APape95](https://github.com/APape95)

## 🙌 Acknowledgements
- Thanks to [TfL Open Data] for the dataset.
- Special mention to the Tableau community for their visualzation tips and resources.
