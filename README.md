# **Google Certified Professional Data Engineer**

## **Chapter 1. Data Processing Fundamentals**
### 1. Data Processing Concepts
**What is Big Data ?** => Big data is large datasets or technology to handle large data. 

**What defines Big Data ?**
We can define BigData with 3V's
1. Volume - The **scale** of information being handled by data processing system.
      
      E.g. MB, GB, TB, PT, ZB, etc.
2. Velocity - The **Speed** at which data is being processed. Ingested, analyzed, visualized.
      
      E.g. AD-HOC, Batched, Near Real-Time, Real Time, etc.
3. Variety - The **diversity** of data sources, formats and quality.
      
      E.g. Key/Valye, Tabular data, Images, Audio, Video, Unstrctured, Mobile/Streaming Data, IOT, etc.
      
**Defining Big Data Terms**
1. Data warehouses & Data Lakes
      | Data warehouses                                   | Data Lakes |
      | --------------------------------------------------| ------------- |
      | Structured and/or Processed - Data is organized, may have been transformed, and is stored in structured way.  |Row & Unstructured - The data lake contains all row, unprocessed data, before any kind of transformation or orgnization. |
      | Ready to Use - Data exists in the warehouse for a defined purpose, and in a format where it is ready to be consumed.| Ready to Analyze - Data is more up to date, but may require more advanced tools for analysis. |
      | Rigid - Data may be easier to understand, but less up-to-date. Structures are hard to change.| Flexible - No structure is enforced, so new types of data can be added at any time. |
   
2. OLTP & OLAP 
      | Online Transactional Processing (OLTP)  | Online Analytical Processing (OLAP) |
      | ------------- | ------------- |
      | High Volume of short Transactions like select or insert stmts in basic SQL terms  | Low volume of long running queries  |
      | Fast Queries  | Analyze the Aggregated Historical Data like generating the reports , Slow Queries  |
      | High Integrity | -  |
      | Modify Database| Query Database  |
   
   **ETL (Extract Transform & Load) prcoesses data from OLTP and move it to OLAP systems.**
3. SQL & NoSQL
      | SQL  | NoSQL |
      | ------------- | ------------- |
      | Strcutured / Tabular Data  | key-value data, JSON Documents, Unstrctured/ Sem-structured Data  |
      | E.g. MySQL, Oracle, etc.  | E.g. MongoDB, cassandra, etc.  |

   ![6433 SQL vs NoSQL](https://github.com/Pallavi0804/Google-Certified-Professional-Data-Engineer/assets/86785954/382b94c1-38b0-4fb4-8426-355e8304055f)

4. Batch & Streaming Data
   | Batch  | Streaming |
   | ------------- | ------------- |
   | Data gathered within a defined window of time   | Continuous collection of Data  |
   | Large volumes of data  | Near real time analytics  |
   | Data from legacy systems  | Windows and micro-batches  |

