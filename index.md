---
layout: cv
title: Pai-Han Su
email:
  url: mailto:patricksuph@gmail.com
  text: patricksuph@gmail.com
homepage:
  url: https://patricksudo.com/
  text: patricksudo.com
github:
  url: https://github.com/PatrickSUDO
  text: github.com/PatrickSUDO
linkedin:
  url: https://www.linkedin.com/in/ph-su/
  text: www.linkedin.com/in/ph-su/
address:
  text: Rotterdam, Netherlands
telephone:
  text: Rotterdam, Netherlands
---


# Pai-Han **Su** <img src="https://media.licdn.com/dms/image/D4E03AQGT5x85guxcfA/profile-displayphoto-shrink_800_800/0/1702080694052?e=1714003200&v=beta&t=1WywKhCPgbOcU3lee9TbAOK5_BskNkaj3KgvAAGyMeo" alt="profile" width="100"/>

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## SKILLS

- Programming Languages: Java, Go, Scala, Python
- Frameworks: Spring Boot, Akka, RabbitMQ
- Cloud Computing: AWS, Azure, Kubernetes, Docker
- Data Stores: PostgreSQL, Elasticsearch, Redis
- DevOps: Terraform, CI/CD(Buildkite), Monitoring(Observability)

## WORK EXPERIENCE

### **JW Player**  `May 2022 - Now`

```
Eindhoven, The Netherlands
```

**_Software Engineer_**

- Developed a **Server-Side Ad Insertion** (SSAI) solution with **Python**, **Golang**, **CDN** to seamlessly stitch ads into **HLS**, **DASH** streams from scratch to production. This initiative led to generating **1.2 billion ad impressions** year to date, with above 80% view rate, handling thousands of requests per second, significantly reducing ad blocking and increasing ad revenue for content-creators.
- Orchestrated system observability using **Datadog**, and automated **CI/CD** pipelines with **Terraform** and **Buildkite**. Enhanced the infrastructure to support the full software development cycle, from Proof of Concept to production, ensuring high availability and performance.
- Built a **Go**-based tracking API to provide in-depth metrics including ad impressions and duration. Data exported for analysis in **Snowflake** via **Airflow**, contributing to strategic data-driven decisions and further optimization of ad performance.
- Focused on customer-centric solutions by working closely with the customer support team to resolve issues and increase service uptime. Actively participated in on-call duties to ensure continuous delivery and quality of service, maintaining system robustness and user satisfaction.

### **Lunatech**  `May 2021 - May 2022`

```
Rotterdam, The Netherlands
```

**_Junior Software Engineer_**

- Enhanced Autonomous Driving Labeling System with **Scala**, **Java**, **Scala.js**, and **Akka**. Used **Elasticsearch** for data streaming.
- Spearheaded the adoption of **Azure DevOps**, automating deployment pipelines, enhancing system monitoring for faster issue resolution, and enforcing network policies to support security compliance.
- Implemented **Agile** and **Scrum** methodologies to enhance team productivity, successfully meeting all key milestones ahead of schedule and improving project delivery.
- Orchestrated a data ingestion pipeline using **Argo Workflow**, improving data preprocessing and task allocation for **machine learning** models.

## PROJECTS EXPERIENCE

### **PaiWallet** | Java, Spring Boot, Spring Cloud, MongoDB, JUnit, Mockito, Redis

- **Challenge**: Creating a secure and efficient digital wallet platform to manage virtual currency, transactions, and user interactions with high availability and scalability.
- **Solution**: Developed a comprehensive digital wallet platform using a **microservices architecture** with **Java**, **Spring Boot**, and **Spring Cloud**. Integrated **Spring Data MongoDB** for ORM and data access, **Redis** for caching, **MongoDB** for data storage. Implemented **Hmily** for distributed transaction management, and **ShardingSphere** for database sharding.
- **Achievements**:
  - Designed and implemented microservices for user authentication, wallet management, P2P transfers, bill payments, and notifications.
  - Achieved fault tolerance and service discovery using **Spring Cloud Netflix** (Eureka and Hystrix).
  - Enhanced performance and scalability through efficient caching mechanisms with **Redis**, and ensured data consistency in distributed environments with **Hmily**.

### **BookList** | Scala, Finagle, Caffeine

- **Challenge**: Needed an efficient way to fetch and display books by author and optional year while maintaining fast response times.
- **Solution**: Developed a **RESTful** service in **Scala** using **Finagle**, and incorporated in-memory caching with **Caffeine**.
- **Achievements**:
  - Achieved comprehensive test coverage by writing unit tests for cache, API client, and main service logic.
  - Utilized in-memory cache with timeout management.
  
### **Dublin Bus Journey Time Predictor** | Python, Django, Machine Learning, Docker, Heroku

- **Challenge**: Predicting bus journey times based on multiple variable factors in a user-friendly way.
- **Solution**: Developed a **RESTful** web application in **Python** using **Django**, with **Machine Learning** models for predictions.
- **Achievements**:
  - Applied exploratory data analysis techniques to fine-tune the tree-based **Machine Learning** model.
  - Successfully deployed the application on **Heroku** using **Docker**, managing both data sets and cloud-based hosting.

## EDUCATION

### **University College Dublin** `Sep 2019 - Dec 2020`

```
Dublin, Ireland
```

**_M.S. Computer Science_**

### **National Taiwan University**   `Sep 2013 - Sep 2015`

```
Taipei, Taiwan
```

**_M.S. Materials Science and Engineering_**

### **National Taiwan University**   `Sep 2009 - Jun 2013`

```
Taipei, Taiwan
```

**_B.S. Chemical Engineering_**

<!-- ### Footer

Last updated: May 2023 -->
