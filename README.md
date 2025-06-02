# -BIG-DATA-ANALYSIS

*COMPANY* : CODTECH IT SOLUTION

*NAME* : Naman Makwana

*INTERN ID* : CT08DM1108

*DOMAIN* : Data Analysis

*MENTOR* : Neela Santosh

*DURATION* : 8 weeks

##To begin Task 3, I wanted to explore how large-scale data can be processed and analyzed efficiently using Apache Spark, a powerful big data framework. Before diving into the implementation, I revised the basics of PySpark, Spark’s Python API, from my notes and online resources like YouTube and ChatGPT. I learned that Spark is especially useful for handling massive datasets because of its speed and distributed computing capabilities.To make my environment ready, I used Google Colab and mounted Google Drive, which allowed me to access a CSV file named “Financial Sample.csv”. I used PySpark’s SparkSession to initialize my Spark application under the name “Scalable Data Analysis”.I started by reading the CSV file into a Spark DataFrame with headers and automatic schema inference. Using df.printSchema(), I inspected the structure and data types of the dataset, and then counted the total number of rows using df.count() to get an idea of the dataset size. The df.show(5) command helped me preview the first few records in a tabular format.After understanding the structure, I initialized a new SparkSession titled “Financial Analysis” for more targeted data processing. I reloaded the dataset to ensure a clean state and focused on the " Profit " column, which originally contained string values with dollar signs and commas (e.g., $5,000). These symbols needed to be removed before any numeric analysis.Using PySpark's regexp_replace function, I created a new column called Profit_Clean by stripping out unwanted characters and converting the strings into numerical format. This conversion allowed me to perform mathematical operations like calculating averages.To gain business insights, I grouped the data by Country and calculated the average profit for each country using the cleaned profit values. I used the agg() function with avg() to perform this aggregation, and sorted the results in descending order to highlight countries with the highest average profits. The output displayed the countries and their corresponding average profit values.This task helped me understand how PySpark simplifies working with large datasets that would be difficult to handle using traditional Python libraries like Pandas. I also saw the real-world relevance of this workflow in areas such as:Financial Reporting – summarizing key metrics by region or product.Business Intelligence – identifying high-performing countries or markets.Scalable Data Processing – handling large volumes of structured data quickly and efficiently.Through this task, I strengthened my understanding of PySpark's DataFrame operations, including data cleaning, transformation, aggregation, and visualization. It reinforced the importance of scalable tools in real-world data analysis projects.

#output

![Image](https://github.com/user-attachments/assets/89a4e2c5-6bd7-464e-8ce9-196f71e6801e)

![Image](https://github.com/user-attachments/assets/35e54016-14e1-43d4-9466-ab37b36938a3)


