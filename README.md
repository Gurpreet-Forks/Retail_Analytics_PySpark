# Retail_Analytics_PySpark

## Introduction 
Data driven decisions have become prominent in multiple sectors over the decades. The benefits linked being manifold, it gained popularity in domains of finance, retail, healthcare, transportation etc. Distributed digital mobility has empowered customers with the accessibility to wide range of markets heterogenous on basis of modes of access, prices, product categories, channels of payment. All this leads to a wide range of data at the hands of industries, directly coming from the end-users. This data is like oil which has to be refined and transformed to fuel the rise in revenue, dip in losses and mitigation of risks. 

One such sector that influences a wide range of population and owns a major share in the market is retail analytics. The way we shop has evolved over the decades from going to markets to purchase what we need to now being persuaded to purchase what we might want. Earlier there were just two stakeholders in the market, the industry and the customer. With time, technology and digital revolution we have seen the emergence of a third stakeholder, “data” 

Retail today is being shaped by empowered customer who demands 
convinience , 
customization 
Collaboration 
Consistency 
To get this right retailers need to empower every decision maker with relevant and accurate insights instantly 

## Spark

Apache Spark is a lightning fast real-time processing framework. It does in-memory computations to analyze data in real-time. It came into picture as Apache Hadoop MapReduce was performing batch processing only and lacked a real-time processing feature. Hence, Apache Spark was introduced as it can perform stream processing in real-time and can also take care of batch processing.
Apart from real-time and batch processing, Apache Spark supports interactive queries and iterative algorithms also. Apache Spark has its own cluster manager, where it can host its application. It leverages Apache Hadoop for both storage and processing. It uses HDFS (Hadoop Distributed File system) for storage and it can run Spark applications on YARN as well.


# "The best of Both Worlds :)"

The PySpark API allows data scientists with experience of Python to write programming logic in the language most familiar to them, use it to perform rapid distributed transformations on large sets of data, and get the results back in Python-friendly notation. PySpark is likely to be of particular interest to users of the “pandas” open-source library, which provides highperformance, easy-to-use data structures and data analysis tools. pandas enables an entire data analysis workflow to be created within Python —rather than in an analytics-specific language such as R —but it is usually limited to running locally and with relatively small data sets. If a data scientist has established a set of pandas-based operations but needs to tackle a much larger data set, PySpark makes it easy to take advantage of distributed compute resources in the cloud, and then bring back a smaller subset of data for further local analysis —all within Python. And because PySpark supports all standard Python libraries and even C extensions, existing code can take advantage of the power of Spark with only minimal modifications.

# "Joining Hands" 

Let me now talk about the use cases that make retail analytics smart Retail Analytics bolstered by Pyspark. 
-Data lake 
-Inventory management 
-Customer segmentation 
-Geographic revenue analysis 
-Product level analysis 

## "The profit yielding lake" : Data Lake 

Data lake :

Harry owns a toy firm. He has a seller’s account in Amazon, Flipkart and Paytm. Moreover, his firm has their own website where purchases can be made. They also own some stores across the country where customer can walk-in, search for what they are looking for and purchase in person. Harry wants to know his customer’s profile so that he can allocate the inventory accordingly to minimize shipping costs. But, Harry is tensed because of the multiple data sources, multiple formats and customers across different locations. 

Solution: 
Using Spark Streaming to dump data from multiple sources in the Hadoop Cluster. Followed by predictive analysis by machine learning models in Python. 


## “Let me clear my stocks" : Inventory Management 

Caroline owns a women apparel brand. She has multiple stores located across locations which serve as offline stores and warehouses for online customers. Caroline is facing a dip in sales. Her inventory at some places is falling short and at some places it is surplus. She learns that data science can help her manage the inventory better, driving sales and bringing in profits. She looks to a data analyst for help. 

Solution by Data Analyst : 
Using PySpark she provides with the following Solution : 
-Mapping of type and amount of stock requirement to different locations based on historical data 
-Knowing what stock to put where. 
-Finding out old stock that can be purchased as per promotions and requirement at different locations. 




