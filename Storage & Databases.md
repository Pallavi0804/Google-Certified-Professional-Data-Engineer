## **Chapter 2. Storage and Databases**
### 1. Introduction to Data Storage in GCP

#### Choosing Data Storage Options:
![image](https://github.com/Pallavi0804/Google-Certified-Professional-Data-Engineer/assets/86785954/47dce9c1-7986-461d-8f41-8c1886410d1b)

**1. Cloud Storage**
    <br>Unstructured object storage.
    <br>It basically provides you with buckets where you can store files.
    <br>Buckets can exist in a single region, two regions, or several regions. All options are durable,but serving from multiple regions can reduce latency.
    <br>Buckets and objects and side buckets can also be classified as standard, nearline, or coldline.
    <br>One key feature of Cloud Storage when handling data is the system of storage event triggers. When an object is written to a Cloud Storage bucket, you can trigger a notification, which can       in turn, cause some other action to happen. This is achieved using Google Pub/Sub.
**2. Cloud Bigtable**
    

