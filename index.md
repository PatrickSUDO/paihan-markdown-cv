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

---

# Pai-Han **Su**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}


## SKILLS
- Programming Languages: Java, Scala, Go, Python, JavaScript
- Frameworks: Spring Boot (Java), Akka (Scala), Django (Python), FastAPI (Python), RabbitMQ
- Cloud Computing: AWS, Azure, Kubernetes, Docker
- Data Stores: PostgreSQL, Elasticsearch, Redis, Snowflake
- DevOps: Terraform, CI/CD (GitLab, Jenkins), Monitoring (Datadog, Prometheus, Grafana)
- Methodologies: Agile, Scrum, SOLID

## EXPERIENCE

### **JW Player**  `May 2022 - Now`

```
Eindhoven, The Netherlands
```

**_Software Engineer_**
- Developed a Server-Side Ad Insertion (SSAI) solution with **Python**, **Golang**, **CDN** to seamlessly stitch ads into HLS, DASH streams from scratch to production. This is now handling thousands of requests per second, significantly reducing ad blocking and increased ad revenue for content-creators.
- Orchestrated system observability using **Datadog**, and automated **CI/CD** pipelines with **Terraform** and **Buildkite**.
- Built a Go-based tracking API to provide in-depth metrics including ad impressions and duration. Data exported for analysis in **Snowflake**.
- Focused on customer-centric solutions by working closely with the customer support team to resolve issues and increase service uptime. Actively participated in on-call duties to ensure high availability and performance.


### **Lunatech**  `May 2021 - May 2022`

```
Rotterdam, The Netherlands
```

**_Junior Software Engineer_**

- Enhanced Autonomous Driving Labeling System with **Scala**, **Scala.js**, and **Akka**. Used **Elasticsearch** for data streaming.
- Led the transition to **Azure DevOps**, automating deployment pipelines, implementing network policies and enhancing system monitoring.
- Drove **Agile** and **Scrum** practices to meet key team milestones.
- Orchestrated a data ingestion pipeline using **Argo Workflow**, improving data preprocessing and task allocation for machine learning models.

## SIDE PROJECTS

### **British Postal Code Distance Calculator** | Spring Boot, PostgreSQL, Mockito, JUnit
- **Challenge**: Creating a reliable and fast service to calculate distances between UK postal codes.
- **Solution**: Developed a **RESTful** service using **Java** and **Spring Boot**, storing postal code data in **PostgreSQL**.
- **Achievements**:
  - Implemented unit tests with Mockito and JUnit to ensure application reliability.
  - Implemented data mapping and regular updates to keep the postal code database current.

### **BookList** | Scala, Finagle, Caffeine
- **Challenge**: Needed an efficient way to fetch and display books by author and optional year while maintaining fast response times.
- **Solution**: Developed a **RESTful** service in **Scala** using **Finagle**, and incorporated in-memory caching with **Caffeine**.
- **Achievements**:
  - Achieved comprehensive test coverage by writing unit tests for cache, API client, and main service logic.
  - Utilized environment variables for secure and flexible API key and cache timeout management.

### **Dublin Bus Journey Time Predictor** | Python, Django, Machine Learning, Docker, Heroku
- **Challenge**: Predicting bus journey times based on multiple variable factors in a user-friendly way.
- **Solution**: Developed a **RESTful** web application in **Python** using **Django**, with **Machine Learning** models for predictions.
- **Achievements**:
  - Applied exploratory data analysis techniques to fine-tune the **Machine Learning** model.
  - Successfully deployed the application on Heroku using **Docker**, managing both data sets and cloud-based hosting.

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
