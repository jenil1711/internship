
# Summer_intership2024_22IT051

This internship will span four weeks and will be full of learning and joy. I am excited about the opportunity to gain hands-on experience in data analysis, work on real-life projects, and collaborate with knowledgeable and supportive colleagues.

 
## Introduction : 4th Sem summer internship 
## Day 1:
Welcome to my github profile this is detailed report of my 4th sem summer internship as data analyst.

starting date : 13/05/2024

   On the very first day of my internship, I had an introductory session with the company colleagues, and it was a very pleasant interaction with the company staff. Mr. Hiren Viradiya, the HR, introduced me to all the office members and provided a brief overview of how the company works on real-life projects and other aspects.


On this day, my guide at the company gave me an overview of the four-week internship, explaining how it would unfold while considering real-life demands and aspects in the field of data science.

## Day 2: 14/05/2024

We are starting with the very popular and useful programming language, Python.

On this day, I got familiar with the features of Python, learned basic syntax, and implemented it. I also got to know about the various libraries that Python offers.

started exploring Numpy library

Today, I started exploring the Numpy library, which provides high-performance multidimensional array objects. Here is a summary of what I learned and implemented:

- Creating Arrays.
- Multidimensional Arrays.
- Created a 2D array using nested lists and examined its shape and structure.
- Practiced reshaping arrays, ensuring the total number of elements remained constant.

## Array Indexing and Slicing
- Accessed specific elements and slices of the array,experimenting with different ranges.
- Demonstrated advanced slicing techniques to retrieve subarrays.

## Array Generation
- Used np.arange to generate an array of numbers with a specific step value.
- Utilized np.linspace to create an array with evenly spaced numbers over a specified range.

## Random Numbers
- Created arrays with random numbers using np.random.rand and np.random.randint.
- Reshaped these random arrays to fit different dimensions.

- This hands-on experience with Numpy has provided me with a solid foundation in handling and manipulating arrays, which are essential skills in data science.
## Day 3: 15/05/2024
➡️ On day 3, I started exploring the Pandas library, a powerful tool for data manipulation and analysis. Pandas provides data structures like Series and DataFrame, which make it easy to handle structured data efficiently. I learned how to create and manipulate DataFrames, import data from various sources, and perform operations.

 🔷 **Reading CSV Files:**
 - Basic CSV Reading: Loaded a CSV file into a DataFrame and viewed its contents.
 - Skipping Rows and Custom Headers: Used parameters like skiprows and header to manage which rows to read and to customize column headers.
- Handling Missing Values: Applied 'na_values' to specify additional strings to recognize as NaN. Customized missing values handling by setting specific values for different columns.
- Reading Partial Data: Limited the number of rows read using 'nrows'. 

 🔷 **Writing to CSV Files:**
 - Basic CSV Writing: Exported a DataFrame to a new CSV file.
 - Customizing Output: Controlled the inclusion of headers and indexes, and selected specific columns for export.

 🔷 **Reading Excel Files:**
 - Basic Excel Reading: Loaded data from an Excel file, specifying the sheet name.
 🔷 **Writing to Excel Files:**
 - Basic Excel Writing: Saved a DataFrame to an Excel file, specifying the sheet name, starting row, and column.
 - Multiple Sheets: Used 'ExcelWriter' to write multiple DataFrames to different sheets within the same Excel file.

( I hade performed all this task practically and attached all the code files in this github repo*).

## Day 4: 16/05/2024

➡️ On the fourth day of my internship, I focused on learning how to handle missing data using the 'replace' method in Pandas. This skill is essential for cleaning and preprocessing datasets to ensure the accuracy and reliability of analyses. Here’s a summary of what I learned:

 🔷 Replacing Single Values:
 - I learned how to replace a specific value with NaN to mark it as missing data. This technique is useful for dealing with placeholder values in datasets.
 🔷 Replacing a List with a Single Value:
 -  practiced replacing multiple placeholder values with a single value to standardize the dataset, which is critical for ensuring consistency.
 🔷 Replacing Per Column:
 - Using a dictionary, I replaced specific values in different columns with NaN. This method allows for targeted cleaning of data columns based on their unique placeholder values.
 🔷 Replacing Using Mapping:
 - I mapped multiple values to new values, such as replacing a placeholder value with NaN or substituting one string for another. This is particularly useful for correcting mislabeled data.
 🔷 Using Regular Expressions (Regex):
 - I used regex to remove unwanted characters from data entries. For example, I removed alphabetic characters from numeric fields, leaving only the numeric values for accurate analysis.
 🔷 Replacing a List with Another List:
 - I replaced qualitative ratings with numeric values to facilitate quantitative analysis. This transformation is crucial for converting categorical data into a format suitable for statistical operations.

 Overall, this day provided me with hands-on experience in handling missing and inconsistent data, which is a vital aspect of data cleaning and preprocessing in the field of data science.
## Day 5: 17/05/2024

➡️ On the fifth day of my internship, I delved into the advanced functionalities of the groupby method in Pandas. This method is a powerful tool for data analysis, allowing for the segmentation of data and performing various computations on these segments. Here’s a detailed account of what I learned and achieved:

🔷 **Weather Data Overview:** 
I worked with a dataset that contains weather information from three cities: New York, Mumbai, and Paris. The dataset includes columns for the day, city, temperature, windspeed, and weather events (such as Rain, Sunny, Fog).

🔷 **Advanced Group By Tasks and Solutions:**
1) Maximum Temperature in Each City:
- One of the first tasks I tackled was to find the maximum temperature recorded in each city. Grouping the data by city allowed me to easily determine these values. For instance, I found that Mumbai had the highest temperature of 92, New York's highest was 36, and Paris's was 54.

2) Average Windspeed in Each City:
- Another task involved calculating the average windspeed for each city. Again, by grouping the data by city, I was able to compute the average windspeed: Mumbai had an average of 9.25, New York averaged 8.00, and Paris averaged 12.75.

➡️  By using the groupby function to group the data by city, I performed several analytical operations:

🔷 Iteration over Groups:

I iterated through each group to inspect the data. This process allowed me to see the weather data for each city separately and identify any patterns or anomalies.

🔷 Extracting a Specific Group:

I extracted the data for Mumbai specifically to focus on the weather patterns in that city. This subset of data provided insights into the frequency of various weather events and the range of temperatures and wind speeds experienced in Mumbai.

🔷 Aggregation Operations: 

I performed various aggregation operations, such as finding the minimum, maximum, and average values for temperature and windspeed in each city. These operations helped summarize the data and provided a clear picture of the weather trends in each location.

🔷 Descriptive Statistics:

I generated descriptive statistics for each group, which included measures like count, mean, standard deviation, minimum, maximum, and quartile values. This comprehensive statistical summary helped in understanding the distribution and central tendencies of the weather data for each city.

Custom Grouping:

Beyond basic grouping, I also explored custom grouping. For instance, I created custom groups based on temperature ranges, grouping days with temperatures between 80 and 90, 50 and 60, and everything else. This custom grouping provided a different perspective on the data, highlighting how often temperatures fell within these specific ranges.


## Week:2

**Day 1: 20/05/2024**

➡️ On the first day of the second week of my internship, I learned about data concatenation using Pandas. This session was crucial for understanding how to merge and prepare data for analysis. Here’s a brief overview of what I learned:

🔷 Basic Concatenation:
- I started with simple concatenation, combining weather data from Indian and US cities into a single DataFrame for comparative analysis.

🔷 Ignoring Indexes:
- Ignoring original indexes during concatenation allows for sequential indexing of the combined data, making it more manageable.

🔷 Using Keys:
- Assigning keys like "india" and "us" during concatenation helped create a hierarchical index, making it easy to differentiate and analyze data from each country.

🔷 Custom Index Concatenation:
- Concatenating DataFrames using a common index, such as city names, provided a comprehensive view of weather conditions by merging temperature and windspeed data.

🔷 Concatenating with Series
- Adding a Series to a DataFrame is useful for incorporating additional attributes. For instance, adding weather events like "Humid," "Dry," and "Rain" to the temperature data enriched the dataset.

🔷 **Practical Applications:**

- Combining Data from Multiple Sources: Essential for creating comprehensive datasets.
- Data Cleaning and Preparation: Merging multiple DataFrames ensures all relevant data is included.
- Hierarchical Indexing: Maintains data structure and integrity.
- Adding New Attributes: Useful in feature engineering for machine learning models.

=> **Conclusion:**

Learning about data concatenation in Pandas has greatly enhanced my data manipulation skills. These techniques are fundamental for efficient data preparation and integration, and I look forward to applying them to more complex datasets as my internship progresses.

▶️  I have also acquired a foundational understanding of Matplotlib, a powerful data visualization library in Python.learned basic syntaxes and understandes the work flow of it.
## Day 2:  21/05/2024

On this day i learned basic about graphes(plotes) such as line plots, scatter plots, histograms, and bar charts. in matplotlib and mastered some of them. 

I have taken dumy dataset and implmented graphes on that data.(all code files are attached in this reposetory)

**1) Line Plot:**

=>   I delved into Matplotlib to visualize data using line plots, exploring its versatile capabilities step by step. I learned how to plot data points with custom line styles and markers, adjust colors and line widths, and include informative titles and axis labels. Understanding concepts like setting plot dimensions, defining axis limits using 'plt.xlim' and 'plt.ylim', and managing ticks with 'plt.xticks' and 'plt.yticks' allowed me to fine-tune the appearance of my plots. Additionally, I mastered saving plots as images ('plt.savefig') for further analysis and reporting. Matplotlib's robust features empowered me to effectively analyze trends and patterns in datasets, making it an invaluable tool throughout my internship.

**2) Bar Plot:**

=>   I gained proficiency in creating bar plots using Matplotlib, which allowed me to effectively visualize and compare data across different categories. I learned to plot bar graphs with customization options such as adjusting bar width (width parameter), aligning bars (align parameter), and changing colors and edge properties (color, edgecolor). Adding informative elements like titles, axis labels (xlabel, ylabel), and legends enhanced the clarity and interpretability of the plots. I also explored advanced features such as setting figure size (figsize), changing plot styles (plt.style.use), and saving plots as images. These skills were invaluable for analyzing and presenting data insights throughout my internship.

**3) Pie Chart:**

=>  I explored creating and customizing Pie Charts using Matplotlib, which allowed me to visually represent and compare relative data proportions effectively. I learned to plot Pie Charts with features such as labeling segments (labels parameter), adjusting label distance (labeldistance), exploding wedges (explode), and setting start angles (startangle). Further customization included changing wedge colors (colors), displaying percentages, adjusting percentage text distance (pctdistance), and modifying wedge properties (wedgeprops). Techniques like changing chart radius (radius), adding shadows (shadow=True), and setting text properties enhanced the clarity and aesthetic appeal of the charts. These skills were instrumental in presenting data insights comprehensively throughout my internship.
## Day 3: 22/05/2024

**4) Scatter plot:**

=> In exploring scatter plots, I learned how to create visualizations that depict the relationship between two variable of used dataset using Matplotlib. I experimented with various customizations, such as changing the size, color, and shape of markers, and added transparency for better visual distinction. Adjusting edge colors and line widths allowed me to emphasize marker boundaries. I also implemented color gradients and colorbars to reflect temperature variations, enhancing the interpretability of the data. Combining scatter plots in one figure enabled me to compare different datasets, and using legends clarified the distinctions between ice cream and tea sales(dataset variables). Finally, setting figure properties like size, background color, and edge color further polished the presentation of the plots.

**5) Histogram plot:**

=> I enhanced my skills in creating histograms using Matplotlib to visualize data distributions. I worked with a dataset to plot histograms, focusing on grouping data into ranges and displaying frequencies with bars of different heights. I customized histograms by adjusting the number of bins, relative bar width, and bar alignment. I experimented with different histogram types, such as step and bar, and varied the orientation to horizontal for better visualization. To further refine the visualizations, I changed bar colors and included multiple histograms in one plot to compare different dataset variables. Additionally, I modified the axis limits, figure size, background color, and plot styles to improve clarity and presentation. This hands-on experience provided me with a comprehensive understanding of how to use histograms to interpret and present data insights effectively.


i have also implemented this plots on various datasets and learned more about this plots.
## Day 4: 23/5/2024

=> As of now, I have acquired foundational knowledge essential for undertaking a data analysis project. To further strengthen my skills and practical understanding, I have begun working with a dataset from a store during a specific Diwali season. The primary objective is to provide insights into sales and revenue performance, aligning closely with the store's requirements.

=> Initially, I conducted an extensive exploration of the dataset to familiarize myself with its structure and contents. This included identifying the types of data available, understanding the number and nature of columns, and assessing the overall data quality.

=> Moving forward, my focus is on performing comprehensive data analysis. I aim to extract meaningful insights that will illuminate sales trends, revenue patterns, and other relevant metrics crucial for assessing the store's performance during Diwali. By applying my knowledge and skills to this real-world dataset, I anticipate deepening my expertise in data analysis techniques and honing my ability to derive actionable conclusions from empirical data.

=> To kick off this project, I commenced by importing the dataset and conducting an initial exploration to understand its structure and contents thoroughly. This preliminary step involved identifying the types of data present, the number of columns, and their respective data types.

=> With a clear grasp of the dataset's composition, i have made outline of this task that what type of insights about data is demanded by store owner by keep in mind the requirement i have created some questions that need to be answered through this task.  so today i have created base of working on a data analysis mini project tommorow we will start the actual implementation.

=> Today's milestone marks the foundation of this data analysis mini-project. Tomorrow, I will delve into the actual implementation phase, applying the knowledge and skills I've acquired to extract meaningful insights from the dataset. This practical application will further enrich my understanding of data analysis techniques and enhance my ability to derive actionable conclusions from real-world data.
## Day 5: 24/05/2024

new day of working on diwali sales data analysis project:
i have analysed the data and gathered insights as mention below:

🔷 Dataset Overview and Preparation
I began by importing and exploring the dataset, which contained 11,239 entries across 13 columns. After an initial assessment of data types and completeness, I made necessary adjustments such as dropping irrelevant columns and handling missing values in the 'Amount' column.

🔷Exploratory Data Analysis (EDA) Highlights
Gender Analysis
I analyzed gender distribution among buyers and observed that females accounted for a majority of purchases. Furthermore, female buyers exhibited higher purchasing power compared to males.

🔷Age Group Analysis
The age group predominantly engaged in purchases was 26-35 years, primarily driven by female buyers within this demographic.

🔷State Analysis
Uttar Pradesh, Maharashtra, and Karnataka emerged as the top states in terms of both order volume and total sales amount, indicating significant market presence during Diwali.

🔷Marital Status and Gender Analysis
Married women were identified as the primary demographic with substantial purchasing power, highlighting their significant contribution to overall sales.

🔷Occupation Analysis
Professionals in IT, Healthcare, and Aviation sectors were found to be the most frequent buyers, suggesting targeted marketing strategies towards these occupational groups could yield higher sales.

🔷Product Category Analysis
Products from categories such as Food, Clothing, and Electronics dominated sales, underscoring consumer preferences during the festive season.

**Conclusion:**

In conclusion, the analysis revealed that married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, employed in IT, Healthcare, and Aviation sectors, were the primary contributors to sales during the Diwali season. Understanding these demographic and behavioral insights is crucial for strategic decision-making and targeted marketing efforts in similar future campaigns.
## Week 3:
**Day 1: 27/05/2024**

As of now i have completed basic of python and libraries and also completed on project based on analysis of a store data.

now i am moving towards my next project which is of analysis of play store data.In this project i will dive deeper in various techniques of data analysis and make grip on that. this project will enhance my practical knowledge and challange my understanding of various python libraries and its method. 

(The dataset of this project is from www.kaggle.com)

Link of dataset :
 https://www.kaggle.com/datasets/lava18/google-play-store-apps


Initial Dataset Exploration:

I began by importing the dataset and inspecting its structure. The dataset comprises 10,841 entries across 13 columns, encompassing app details such as name, category, rating, reviews, and more.

Data Cleaning and Preprocessing:

Checked for missing values and identified columns needing data type adjustments.
Addressed inconsistencies in the 'Reviews' column, converting it to numeric format to facilitate analysis.
Exploratory Data Analysis (EDA):

Basic Statistics: Utilized describe() to get an overview of numeric columns.

Category Analysis: Explored the number of unique categories and identified which categories received the highest average ratings.

Rating Analysis: Calculated the average app rating and identified apps with the maximum number of 5-star ratings.
Type of Apps: Differentiated between free and paid apps, analyzing their distribution and average ratings.
Insights Gained:

Discovered that the average rating for paid apps is slightly higher than that for free apps.
Identified "Facebook" as the app with the maximum number of reviews in the dataset.

This project is ongoing, and further work will continue tomorrow..
## Day 2: 28/05/2024

Today i will continue my pending projecct which is about google play store data analysis.

🔷Further Data Exploration:

**Genre Analysis:** 

=> Explored the distribution of app genres and identified popular genres among users.

Content Rating Distribution: Analyzed the distribution of content ratings to understand the preferences of different audience segments.

=> App Installs Analysis: Investigated the distribution of app installations across different categories to identify categories with the highest user bases.
Visualization and Insights:

=> Created visualizations such as bar plots, histograms, and pie charts to illustrate the distribution and relationships within the dataset.
Visualized which categories and genres have the most apps and which are most highly rated.
Explored correlations between variables like app size, price, and ratings using scatter plots and heatmaps.


**Conclusion:**
This project has significantly enhanced my proficiency in Python programming and data manipulation using Pandas. Analyzing factors such as app ratings, reviews, categories, genres, and content ratings provided valuable insights into consumer preferences and market trends on the Google Playstore.

## Day 3: 29/05/2024

After successfully completing two projects, I am now embarking on a more challenging and significant endeavor: sales data analysis for a seller who operates an e-commerce platform. 

🔷 This project involves a detailed examination of sales data to provide comprehensive insights into the seller's business. Through rigorous analysis, I will uncover trends in sales performance, identify top-selling products, and determine which items are underperforming. Additionally, I will evaluate the optimal timing for advertising campaigns to maximize customer engagement and conversion rates. By leveraging advanced analytical techniques, this analysis aims to deliver actionable recommendations that will empower the seller to make informed decisions to enhance sales and overall business growth.

On the first day of the project, the primary focus was on collecting and preparing the raw data for analysis. Utilizing Python and Pandas libraries, I initiated the process by importing and consolidating multiple CSV files containing sales data from different months of the year 2019. This step involved creating a comprehensive dataset named "all_data.csv" that aggregated all individual monthly sales records into a unified format.

=> Following data aggregation, thorough data cleaning procedures > were implemented to ensure the dataset's integrity and readiness for analysis. Key tasks included handling missing values (NaN), which were identified and either removed or replaced with appropriate values where necessary. Additionally, data types were meticulously converted to their correct formats, such as converting "Quantity Ordered" to integer type and "Price Each" to float type, ensuring accurate numerical operations moving forward.

**Conclusion of the Day :**

On the first day of work, we focused on organizing and cleaning up the sales data to create a solid foundation for our analysis. This involved consolidating all the sales data into a single file called "all_data.csv" after gathering it from multiple sources. By doing this, we ensured that the data was consistent and ready for detailed examination. This cleaned-up dataset became our starting point for deeper exploration and allowed us to uncover meaningful insights that could drive actionable decisions for the business.


## Day 4: 30/05/2024

Day 2: Exploratory Data Analysis (EDA)

Day two of the project was dedicated to conducting exploratory data analysis (EDA) on the cleaned dataset. This phase aimed to uncover meaningful patterns, trends, and insights that could provide valuable business intelligence. The initial step involved identifying the best-performing month in terms of sales volume and revenue. Visual representations, such as bar charts, were employed to effectively communicate these findings.

Moreover, geographical analysis was conducted to determine which city had the highest sales. This analysis provided geographical context and highlighted regional sales performance disparities. Additionally, I investigated the timing of customer purchases to optimize advertising strategies. By identifying peak hours for customer engagement through detailed analysis of order timestamps, strategic insights were gained on when advertisements should be deployed to maximize customer response and sales potential.

**Conclusion of the Day:**

Day two's exploratory data analysis yielded crucial insights into sales performance across different dimensions. By identifying peak sales months, regional variations in sales, and optimal advertisement timings, we gained actionable intelligence for refining marketing strategies and operational decisions. The visualizations and analyses conducted provided a clear understanding of the dataset's dynamics and paved the way for deeper product-focused investigations on the final day.
## Day 5: 31/05/2024

Day 3: Product Insights and Recommendations

The final day of the project focused on gaining insights into product performance and deriving actionable recommendations based on the findings. Market basket analysis techniques were applied to identify products frequently purchased together, uncovering potential cross-selling opportunities. This analysis highlighted product combinations that customers commonly bought in tandem, offering insights into consumer preferences and purchasing behavior.

Furthermore, I investigated which products sold the most overall and explored possible reasons for their popularity. By analyzing both quantity ordered and average price data, I identified top-selling products and provided insights into factors contributing to their market success. These findings were crucial for formulating recommendations aimed at optimizing product offerings and enhancing marketing strategies to drive sales and profitability.

Conclusion for Day 3:
Day three's focus on product insights and recommendations provided actionable strategies for enhancing business performance. By leveraging market basket analysis and identifying top-selling products, we gained valuable insights into consumer behavior and preferences. The recommendations derived from this analysis, such as refining product bundles and targeted marketing campaigns, aimed to capitalize on identified strengths and drive future growth and profitability.

**Overall Project Conclusion:**

Throughout this three-day project, I successfully executed a comprehensive analysis of sales data from 2019, transforming raw data into actionable insights. By consolidating data, conducting exploratory analyses, and deriving product-focused recommendations, I provided valuable strategic insights for optimizing business operations and enhancing market competitiveness. Moving forward, these insights can guide informed decision-making and drive sustainable growth in sales and profitability.
## Week 4:

Day 1: 3/06/2024

I have implemented 3 data analysis projects, in these three  projects, I have gained invaluable insights into the realm of data analysis. Now, I am eager to transition into the domain of data visualization, recognizing its pivotal role in deriving actionable insights. Visual representations such as charts and graphs often convey complex information more effectively than text alone, facilitating easier interpretation and decision-making. To deepen my expertise in this critical area, I have embarked on a focused learning journey with Microsoft's Power BI, a leading business analytics tool. Over the course of this week, my objective is to master Power BI's capabilities in visualizing data, enabling me to deliver compelling insights that drive informed business decisions.


on the very first day of week 4 i have learned about data visualization and explored many things regarding this topic.

=> I delved into learning about Power BI, a powerful business intelligence tool. Power BI allows for intuitive data visualization and analysis, which is crucial for deriving insights from large datasets. I began by understanding the basic concepts of Power BI, such as data modeling, creating relationships between different data sources, and designing interactive dashboards.
## Day 2: 4/06/2024

=> I engaged in hands-on practice with Power BI. I explored various features such as importing data from different sources, transforming data to suit analytical needs, and creating calculated columns and measures to derive specific metrics. This practical experience enhanced my understanding of how to manipulate data within Power BI to produce meaningful visualizations.

=> also i applied my knowledge to build my first Power BI dashboard. Starting from scratch, I imported a dataset of amazon prime videos, designed interactive visualizations including charts, graphs, and KPIs (Key Performance Indicators), and created a coherent layout for the dashboard. This exercise allowed me to showcase my ability to translate raw data into actionable insights using Power BI. This dashboard contains details like number of shows, number of directors, geners, yearly release shows and many details.

I have uploaded this dashboard in my github.(repo* name: internship/dashboard-2.png)
## Day 3: 5/07/2024

after gaining basic knowledge of power bi and data visulization now i am moving further to gain advanced knowledge of power  bi.

=> Thoday is dedicated to refining and enhancing the initial Power BI dashboard. I focused on improving the usability and aesthetics of the dashboard by incorporating filters, slicers, and tooltips to enhance interactivity. Additionally, I explored advanced features such as drill-down capabilities and integrating custom visuals to provide deeper insights into the data. This iterative process helped me create a more comprehensive and user-friendly dashboard.


## Day 4: 6/06/2024

on this day i have created one advanced project on power bi.

i have created advanced and interacte power bi dashboard on the data of a super market. through this dashboard i have provided many insights about sales of this stores. one can easily understand and manage store by working with this dashboard. in this dashboard i have added functionalities like sales by state for which i have provided map, monthalu profit, yearly profit and region wise filtering and many more.

i have also done sales forecasting for this sales data and done it for next months using dax queries and other features.

I have uploaded this dashboard in my github.(repo* name: internship/dashboard-1.png)
## Day 5: 7/07/2024

completion of internship.

=> created final documents and submited all works of 4 weeks. 