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
phone: "+31657256350"
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

- Programming Languages: Java, Go, Python
- Frameworks: Spring Boot, Akka, RabbitMQ
- Cloud Computing: AWS, Azure, Kubernetes, Docker
- Data Stores: PostgreSQL, Redis
- DevOps: Terraform, CI/CD(Buildkite), Datadog(Observability)

## WORK EXPERIENCE

### **JW Player**  `May 2022 - Now`

```
Eindhoven, The Netherlands
```

**_Software Engineer_**

- In a collaborative team of five, developed a **Server-Side Ad Insertion** (SSAI) solution with **Python**, **Golang**, **CDN** to seamlessly stitch ads into **HLS**, **DASH** streams from scratch to production. This initiative led to generating **1.2 billion ad impressions** year to date, with above 80% view rate, handling over **200K** requests per second, significantly reducing ad blocking and increasing ad revenue for content-creators.
- Orchestrated system observability using **AWS CloudWatch** and **Datadog**, and automated **CI/CD** pipelines with **Terraform** and **Buildkite**. Enhanced the **AWS** infrastructure to support the full software development cycle, from Proof of Concept to production, ensuring high availability and performance.
- Built a **Go**-based tracking API to provide in-depth metrics including ad impressions and duration. Data exported for analysis in **Snowflake** via **Airflow**, contributing to strategic data-driven decisions and further optimization of ad performance.
- Focused on customer-centric solutions by working closely with the customer support team to resolve issues and increase service uptime. Actively participated in on-call duties to ensure continuous delivery and quality of service, maintaining system robustness and user satisfaction.

### **Lunatech**  `May 2021 - May 2022`

```
Rotterdam, The Netherlands
```

**_Junior Software Engineer_**

- Enhanced Autonomous Driving Labeling System with **Scala**, **Java**, **Scala.js**, and **Akka**. Used **Elasticsearch** for data streaming.
- Spearheaded the adoption of **Azure DevOps**, automating deployment pipelines, enhancing system monitoring for faster issue resolution, and enforcing network policies to support security compliance.
- Implemented **Agile** and **Scrum** methodologies, including daily stand-ups, sprint planning, story refinement, and retrospectives, significantly enhancing team productivity and project delivery.
- Orchestrated a data ingestion pipeline using **Argo Workflow**, improving data preprocessing and task allocation for **machine learning** models.

## PROJECTS EXPERIENCE
 
### **PaiWallet** | Java, Spring Boot, Spring Cloud, Eureka, MongoDB, JUnit, Mockito, Redis `Feb 2024 - Now`

- **Challenge**: Creating a secure and robust digital wallet platform capable of managing virtual currency and handling high-concurrency transactions, while ensuring scalability.
- **Solution**: Developed a digital wallet using **microservices** architecture with **Java** technologies, achieving robust transaction handling and service reliability.
- **Achievements**:
  - Architected services including **JWT** user authentication, wallet management, P2P transfers, bill payments, and notifications, enabling the system to efficiently manage up to **10K** transactions per second, thereby enhancing transaction capacity and system responsiveness.

### **BookList** | Scala, Finagle, Caffeine `May 2023 - Jun 2023`

- **Challenge**: Ensured **sub-100ms** response times for fetching and displaying book data across various filters.
- **Solution**: Developed a **RESTful** service in **Scala** using **Finagle**, and incorporated in-memory caching with **Caffeine**.
- **Achievements**:
  - Enhanced data retrieval efficiency and reduced server response times by about 35%% through optimized caching strategies.
  - Achieved 95% test coverage, demonstrating thorough validation and reliability of service components.

### **Dublin Bus Journey Time Predictor** | Python, Django, Machine Learning, Docker, Heroku `Jul 2020 - Aug 2020`

- **Challenge**: Developed a machine learning model to predict bus journey times with a mean absolute percentage error(MAPE) of approximately **5%**.
- **Solution**: Implemented a user-friendly **RESTful** web application in **Python** using **Django**, integrating **Light Gradient Boost Model(LGBM)** models for accurate predictions.
- **Achievements**:
  - Deployed the application using **Docker** on **Heroku**, ensuring efficient cloud-based data management and application hosting.
  - Accurately predicted bus journey times by incorporating real-time bus schedules and weather data into the analysis.

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
