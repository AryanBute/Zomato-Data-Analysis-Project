🍽️ Zomato Restaurant Data Analysis
An exploratory data analysis (EDA) project on Zomato restaurant data to uncover insights about restaurant types, ratings, online ordering trends, and customer preferences.

📁 Project Structure
├── Zomato_DA.ipynb       # Main Jupyter Notebook with full analysis
├── Zomato_data_.csv      # Dataset used for analysis
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

📊 Dataset
The dataset contains information about restaurants listed on Zomato with the following columns:
ColumnDescriptionnameRestaurant nameonline_orderWhether online ordering is available (Yes/No)book_tableWhether table booking is available (Yes/No)rateCustomer rating (out of 5)votesNumber of votes/reviewsapprox_cost(for two people)Approximate cost for two people (INR)listed_in(type)Type/category of restaurant

🔍 Analysis Performed

Restaurant Type Distribution — Count of restaurants by category using bar plots
Votes by Restaurant Type — Which restaurant types receive the most engagement
Rating Distribution — Histogram of restaurant ratings
Cost Analysis — Distribution of approximate cost for two people
Online Order vs Rating — Box plot comparing ratings based on online ordering availability
Heatmap — Relationship between restaurant type and online ordering using a pivot heatmap


🚀 Getting Started
1. Clone the repository
bashgit clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
2. Install dependencies
bashpip install -r requirements.txt
3. Launch Jupyter Notebook
bashjupyter notebook Zomato_DA.ipynb

🛠️ Tech Stack

Python 3.x
Pandas — Data manipulation
NumPy — Numerical operations
Matplotlib — Data visualization
Seaborn — Statistical plots
Jupyter Notebook — Interactive analysis environment


📌 Key Insights

Dining restaurants dominate the listings compared to other types
Restaurants with online ordering tend to have different rating distributions
Most restaurants fall in the ₹300–₹800 range for two people


📄 License
This project is open-source and available under the MIT License.
