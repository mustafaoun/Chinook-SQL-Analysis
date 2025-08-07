#  Music Company Data Analysis Project (Chinook DB)

This project performs a data-driven analysis of a music company's sales, customer, and content data. The goal is to provide key business insights and actionable recommendations to optimize performance, increase revenue, and improve customer engagement.

---

##  Data Schema Overview

The analysis is based on a relational database schema with tables representing core business entities and their relationships. Key tables include:

- **invoice & invoice_line**: Contains all sales transaction data.  
- **customer & employee**: Stores information about customers and the support representatives who assist them.  
- **track, album, artist, genre**: Details the music content catalog and its structure.  
- **playlist**: Manages curated track lists.

---

##  Analytical Questions

The following questions were posed to guide the analysis, categorized by business area:

###  Sales & Revenue
- Which artists and genres generate the most revenue?  
- What is the average order value (AOV)?  
- Which media types are most commonly sold?

###  Customer Analysis
- Which customers have spent the most money in total?  
- What is the distribution of customer spending?  
- How many customers have not made a purchase in the last year?

###  Employee & Performance
- Which employee is assigned to the most valuable customers?  
- How does the number of customers per support rep compare to their total sales?

###  Content & Product
- What are the top 5 most popular playlists?  
- What is the average number of tracks per album?

---

## Key Insights

- **Revenue Drivers**: Rock and Latin music are the primary revenue generators. Top artists like *Iron Maiden* and *U2* are strong contributors. Interestingly, non-music content like *The Office* also shows success.
- **Customer Behavior**: The average order value is low at **$5.65**, suggesting small, frequent purchases. Many customers are low spenders, and **59 customers** have been inactive for over a year.
- **Employee Performance**: Representatives with larger customer portfolios, like **Jane Peacock**, tend to drive more total sales.
- **Content Trends**: The "Music" playlist is the central hub. Curated playlists like "90's Music" and "TV Shows" show strong demand for focused content.

---

##  Recommendations

- **Increase Customer Spending**: Offer bundled discounts and loyalty rewards to encourage higher AOV.
- **Improve Retention**: Re-engage inactive customers with personalized email campaigns and targeted promotions.
- **Optimize Content Strategy**: Focus on Rock and Latin genres. Create more targeted playlists to align with user interests.
- **Leverage Top Performers**: Analyze how top reps like Jane Peacock manage clients and scale those strategies across the team.

---

##  Technologies Used

- **SQL**: For querying and extracting data.
- **Python**: For data manipulation and analysis.
- **Pandas**: For dataframe handling and processing.
- **Matplotlib / Seaborn**: For data visualization.

---

