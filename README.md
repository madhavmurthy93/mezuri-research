Mezuri Platform - Research in Change Group, University of Washington
===============
The Mezuri Platform is a hardware and software system for end-to-end management of data from development interventions. Read more about it on this [Mezuri](http://dil.berkeley.edu/data-analytics-toolkits/mezuri-platform/) article. The platform is still in development and so the code is not publicly available yet.

### Research
I spent Summer 2014 working on research in the field of Information and Communication Technology for Development (ICTD) in Gaetano Borriello's lab at the UW CSE department. I specifically worked on developing the cloud-based data storage for the Mezuri Platform by building on an existing data management platform ([ODK Aggregate](https://opendatakit.org/use/aggregate/)) built by the ICTD lab. The datastore service was built on top of [Google Cloud SQL](https://cloud.google.com/sql/docs) for database storage and [Google Cloud Storage](https://cloud.google.com/storage/docs) for blob storage. It was built as a REST interface compatible with the [ODK 2.0](https://code.google.com/p/opendatakit/wiki/REST_Synchronization_API) interface. 

### Features
- Table API & Table Definition API to create, view and delete tables
- Data API to insert, view, update and delete rows
- Blob Storage API to insert, view and delete files
- Metadata storage to track provenance

### Learning Outcomes
- Database design
- REST interface design
- Building web services
- Using Google Cloud Platform
- Docker basics

### Languages & Technologies
```
Java, Python, SQL, JDBC, Apache Tomcat, Apache Maven, Apache Wink, Docker API, Google Cloud Storage API
```

