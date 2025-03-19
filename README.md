🥘 Indian Food Data Analysis
📊 Overview
This project is a comprehensive data analysis and visualization of Indian cuisine, using a curated dataset containing various Indian dishes with details like ingredients, region, course, cook time, flavor profile, and more.

From identifying the most common ingredients to comparing flavor preferences across regions — this project uncovers interesting culinary insights while showcasing solid data wrangling, cleaning, and visualization skills.

📁 Dataset Summary
Source: Indian Food Dataset (CSV format)
Features:
name: Dish name
ingredients: Comma-separated list of ingredients
diet: Veg / Non-Veg
flavor_profile: Spicy / Sweet / Tangy / Mild
course: Course type (Main, Snack, Dessert, etc.)
state: Indian state of origin
region: Broader region (North, South, East, etc.)
prep_time, cook_time: Time in minutes
total_time: Calculated field (prep_time + cook_time)
🔧 Data Cleaning Highlights
Replaced all missing or invalid values (-1) in time and categorical columns
Merged duplicate state names (e.g., NCT of Delhi → Delhi)
Standardized ingredient strings for consistent analysis
📊 Exploratory Data Analysis
✅ Univariate Analysis
Histograms, KDE plots, boxplots, and bar charts for understanding each column independently.
✅ Bivariate Analysis
Scatter plots, grouped bar charts, and boxplots comparing columns like:
diet vs state
flavor_profile vs region
course vs cook_time
prep_time vs cook_time
✅ Correlation Heatmap
Analyzed numerical columns to identify trends or strong correlations.
✅ Ingredient Frequency
Identified the top 15 most commonly used ingredients across all dishes.
Gained insight into the building blocks of Indian cuisine (hello onions, tomatoes, turmeric 🌶️)
🧠 Key Insights
South Indian food dominates spicy flavor profiles
Desserts are the fastest to cook (sweet in every way)
Prep time doesn't always predict cook time!
Veg dishes are more frequent across most regions
Some ingredients are universal — others define regional identity
🛠️ Tech Stack
Python 🐍
Pandas & NumPy for data cleaning
Matplotlib & Seaborn for visualization
Jupyter Notebook for analysis and experimentation
💡 What's Next?
Create interactive dashboards using Plotly or Streamlit
Perform clustering based on ingredients or regions
Build a recipe recommendation system based on similarity
📌 Final Note
This project is part of my data science learning journey — blending a love for food and code!
Feel free to explore, fork, or contribute 🍽️💻

