# Airbnb Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on an Airbnb dataset to understand the distribution, pricing, reviews, and availability of listings. Interactive **Plotly visualizations** are used to explore trends and patterns in the data.

The goal is to uncover insights such as:
- Price distribution across neighborhoods and room types  
- Popular neighborhoods and room types  
- Review activity and availability patterns  
- Geographic distribution of listings  

---

## 🗂 Dataset
The dataset contains Airbnb listings with the following key columns:

| Column | Description |
|--------|-------------|
| `id` | Listing ID |
| `name` | Name of the listing |
| `host_id` | Host ID |
| `host_name` | Host name |
| `neighbourhood_group` | City borough (e.g., Manhattan, Brooklyn) |
| `neighbourhood` | Specific neighborhood |
| `latitude` | Latitude coordinate |
| `longitude` | Longitude coordinate |
| `room_type` | Room type (Entire home/apt, Private room, Shared room) |
| `price` | Listing price in USD |
| `minimum_nights` | Minimum number of nights per booking |
| `number_of_reviews` | Total number of reviews |
| `last_review` | Date of last review |
| `reviews_per_month` | Average reviews per month |
| `calculated_host_listings_count` | Number of listings per host |
| `availability_365` | Availability over 365 days |

> Note: The project includes both the **raw dataset** and a **cleaned version** used for analysis.

---

## 📊 Visualizations
The project contains the following interactive visualizations using **Plotly**:

1. **Listings per Neighborhood** – Histogram of listings by neighborhood  
2. **Price Distribution** – Histogram with boxplot of prices  
3. **Average Price by Room Type** – Bar chart of average prices per room type  
4. **Reviews vs Price** – Scatter plot of number of reviews against price  
5. **Availability Heatmap** – Heatmap of average availability per neighborhood and room type  
6. **Listings per Neighbourhood Group** – Histogram by borough, colored by room type  
7. **Top 10 Neighbourhoods by Average Price** – Bar chart of most expensive neighborhoods  
8. **Price vs Minimum Nights** – Scatter plot highlighting extreme listings  
9. **Reviews per Month vs Price** – Scatter plot to analyze review activity  
10. **Map of Listings** – Geographic scatter map showing listing locations, price, and room type  

---

## 🛠 Tools & Libraries
- **Python 3.x**  
- **Pandas** – Data manipulation  
- **Plotly Express** – Interactive visualizations  
- **NumPy** – Numerical operations  

---

## 🔄 Usage
1. Clone the repository:
```bash
git clone https://github.com/chrollolucifr/HomeTask_week3_9-24-2025.git

Install required libraries:
pip install pandas numpy plotly
