Directory Structure
-------------------
css\              - Stylesheets CSS files for the template.
images\           - Images used in template.
scripts\          - JavaScript used in the template.
styles\           - SCSS source files for stylesheets CSS. Available in Purchased versions only.
favicon.ico       - Favicon placeholder provided for the template.
index.html        - Main HTML page to open the template in browser.
*.html            - Additional HTML pages (if any).
LICENSE-*.txt     - License file as per your downloaded variant.

How to Edit the template
------------------------

1. Editing Content in template

To edit the content open the corresponding *.html files and open them
in an editor such as VSCode or Notepad++.
Search for the content you want to change and edit it to the text you want.
Save the file and reopen HTML file in browser to see the changes.

2. Editing Styles of template

The main style is present in css\main.css which you can edit.
You must know how to edit CSS files to do this.
If you have purchased any of the premium version then you will also get
SCSS source files which generates all the styles of the template.
You can use these SCSS files to make your changes and regenerate CSS.

3. Changing Images

You can change images inside the images\ folder.
Make sure to name the file same as the original file.
If you wish to change the name of the image file then you must
also make corresponding change in the HTML file which refer to that image.

How to use the template
-----------------------
Upload the contents to your webserver.
index.html must be in the main (root) folder of your webserver.
Do not change the name of the template folders or files unless you know
what you are doing and are changing the names in HTML files too.
For webhosting, you can go with https://templateflip.com/go/hosting for easy FTP file uploads.


# Jay Kumar

**Data Scientist | AI Developer | Python Developer | Machine Learning Researcher**  
Halifax, NS, Canada | Email | Phone | LinkedIn | GitHub | Portfolio

---

## Professional Summary

Results-oriented Data Scientist, AI Developer, Python Specialist, and Machine Learning Researcher with experience building machine learning models, geospatial analytics workflows, backend APIs, ETL pipelines, dashboards, and AI-powered search systems. Strong background in Python, SQL, FastAPI, machine learning, NLP, time-series forecasting, geospatial analytics, RAG/vector search, and cloud data engineering. Experienced in working with large-scale AIS vessel tracking data, ocean sensor datasets, short-text NLP datasets, and enterprise database-backed systems. Proven ability to develop end-to-end technical solutions, from data extraction and preprocessing to model development, API deployment, visualization, reporting, and stakeholder documentation. Skilled in translating complex analytics into practical tools for researchers, data managers, industry users, and decision-makers.

---

## Core Skills

**Programming & Scripting:** Python, SQL, Java, JavaScript, PHP, PowerShell, Linux Bash  
**Data Science & Machine Learning:** Scikit-learn, TensorFlow, PyTorch, Random Forest, SVM, Transformer Models, Time-Series Forecasting, Anomaly Detection, Classification, Clustering, Feature Engineering  
**NLP & AI:** NLP, BERT, TF-IDF, LDA Topic Modeling, Gensim, NLTK, spaCy, LangChain, Hugging Face, Sentence Transformers, Llama, RAG, Vector Search, FAISS  
**Data Engineering & Analytics:** ETL Pipelines, Data Warehousing, Data Cleaning, Data Transformation, Batch Pipelines, Spark, PySpark, Pandas, NumPy, Data Partitioning, Parquet  
**Backend & API Development:** FastAPI, REST APIs, Flask REST API, JSON, API Documentation, Model Serving, Database-Backed Services  
**Databases & Storage:** PostgreSQL, PostGIS, MySQL, Oracle, BigQuery, Bigtable, SQL Optimization, Stored Procedures, Complex Joins, Aggregations, CSV, GeoJSON, Shapefiles, NetCDF  
**Geospatial & GIS:** GeoPandas, Shapely, QGIS, Spatial Joins, KDTree/SciPy, Spatial Indexing, Route Polygons, Grid Cells, Geospatial Time-Series Data  
**Cloud & DevOps:** Google Cloud Platform, Vertex AI, Cloud Storage, Dataflow, Pub/Sub, Docker, Docker Compose, Databricks, Linux Server, GitHub Actions CI/CD  
**Visualization & Reporting:** Tableau, Looker, Streamlit, Plotly, Matplotlib, Seaborn, Jasper Reports, Dashboards, KPI Reporting, Technical Reports, Stakeholder Presentations  
**Testing & Collaboration:** PyTest, Selenium, GitHub Actions, JIRA, Git, SVN, Documentation, Research Writing, Cross-Functional Collaboration

---

## Professional Experience

### CIOOS Atlantic | Halifax, NS, Canada

**Artificial Intelligence Developer | AI Developer | Data Developer**  
**08/2024 – 07/2025**

- Developed tools, APIs, and analytics workflows for **103 ocean geospatial time-series sensor datasets**, including sea surface temperature, ocean waves, weather, currents, dissolved oxygen, and salinity, improving usability for researchers, industry users, and internal data-management teams.
- Built a **Python dataset-overlap and recommendation package** to identify similar ocean datasets using spatial overlap, temporal coverage, and variable/attribute similarity.
- Implemented **hexagonal-grid spatial similarity** using 20-km grid coverage to compare geographic overlap between datasets and account for imperfect latitude/longitude alignment across data sources.
- Developed **daily-window temporal similarity logic** to compare dataset time coverage and support discovery of related datasets across different collection periods.
- Designed **weighted recommendation scoring** combining spatial overlap and attribute similarity to rank and recommend related datasets, improving dataset recommendation efficiency by **30%**.
- Compared variables across all datasets to identify shared attributes, overlapping ocean concepts, and interoperability issues caused by inconsistent contributor naming conventions.
- Found **45% overlapping concept terms** across dataset features and metadata concepts.
- Developed **FastAPI endpoints** to return recommended/similar datasets, retrieve overlap scores, serve data to dashboards/maps, and expose QA/QC anomaly-detection results.
- Built Python/SQL ETL pipelines to extract metadata from **CKAN catalog and ERDDAP pages** using Selenium, parse `.das` metadata files, clean variable names, attributes, and keywords, transform geospatial/time-series records, and validate data quality and boundary information.
- Loaded processed temporal coverage data into **PostgreSQL** and maintained CSV-based keyword tables to support metadata enrichment, searchability analysis, and dataset discovery workflows.
- Built **vector search and RAG functionality** over dataset descriptions and summaries using **Hugging Face embeddings, Sentence Transformers, LangChain, FAISS, Llama, and custom Python retrieval pipelines** to generate natural-language search answers and improve semantic dataset discovery.
- Created QA/QC anomaly-detection features for **sea surface temperature, dissolved oxygen, and salinity** using rolling standard deviation, past-window mean deviation, and upper/lower quantile threshold rules.
- Created dataset overlap heatmaps, spatial coverage maps, user search/access-log analysis visuals, keyword/searchability analysis, and stakeholder summary reports using **QGIS, FastAPI, Matplotlib, Plotly, Streamlit, Pandas, and NumPy**.
- Analyzed CKAN/ERDDAP user behavior from **70,000+ unique IPs**, including approximately **3,100 search users** and **750 unique search terms**, to understand search patterns and improve dataset discoverability.
- Identified **20+ incorrect dataset boundaries** and documented issues where square bounding boxes did not accurately represent actual polygon-based dataset coverage, supporting more accurate geospatial search and data access.
- Improved metadata quality and searchability by identifying non-useful or ambiguous keywords, recommending better keyword-generation strategies, and using dataset summaries to support more relevant metadata enrichment.
- Implemented **PyTest unit tests** for the Python recommendation package, automated data-extraction checks, and Selenium-based tests for CKAN, ERDDAP, and CIOOS Data Explorer pages.
- Configured **GitHub Actions CI/CD workflows** to run PyTest unit tests and automate Python package build/release processes.
- Collaborated with **data managers, project managers, and ocean researchers** to improve ocean dataset discovery, metadata quality, recommendation workflows, QA/QC analysis, and stakeholder-facing reporting.

**Technologies:** Python, SQL, FastAPI, PostgreSQL, Selenium, PyTest, GitHub Actions, Pandas, NumPy, Matplotlib, Plotly, Streamlit, QGIS, FAISS, LangChain, Hugging Face, Sentence Transformers, Llama, RAG, vector search, CKAN, ERDDAP.

---

### Dalhousie University | Halifax, NS, Canada

**Data Scientist | ML Research Scientist | Python Developer**  
**01/2022 – 05/2024**

- Developed machine learning, geospatial analytics, and Python-based data pipelines for **ship movement prediction, maritime traffic forecasting, vessel anomaly detection, and fishing activity analysis**.
- Processed **6 years of AIS vessel-tracking data** from Canadian waters, covering **12+ vessel/ship types**, approximately **2,000 vessels**, and monthly AIS volumes of **60–80 million records**.
- Worked with AIS features including **MMSI/vessel identifier, latitude, longitude, timestamps, speed over ground, course over ground, heading, vessel type, destination, port/route/traffic-zone data, and historical trajectory records**.
- Preprocessed AIS data by filtering messages by geographic region and vessel type, removing low-speed or anchored vessel pings, cleaning invalid MMSI identifiers, and handling missing or unreliable destination fields.
- Converted raw AIS pings into vessel tracks/voyages using time-gap and distance-gap thresholds, including an **8-hour time-gap threshold** and **50 km distance-gap threshold** for track construction.
- Resampled vessel trajectories at **5-minute and 10-minute intervals**, selecting **10-minute resampling** for model efficiency and producing **72 forecasted points** for each 12-hour trajectory prediction.
- Converted vessel positions into **500-meter grid-cell representations** and used route polygons, destination grid cells, and current grid-cell centroids to support route-aware forecasting.
- Used **KDTree spatial indexing** to accelerate spatial joins between AIS trajectories and contextual datasets, reducing spatial data retrieval/joining time by **90%**.
- Integrated AIS data with weather, ocean, port, route, satellite, and sensor datasets to enrich trajectory modeling and maritime analytics workflows.
- Built a **Transformer encoder–based deep learning model** to forecast full future vessel trajectory sequences **12 hours ahead**.
- Engineered probabilistic grid-cell destination features to improve route/destination awareness and support multi-path long-term vessel trajectory forecasting.
- Used model input features including longitude, latitude, speed over ground, course over ground, current grid-cell centroid, route polygon centroid, destination grid-cell centroid, vessel type, and heading.
- Evaluated the trajectory forecasting model using **RMSE in kilometers**, **trajectory coverage percentage**, and visual comparison of predicted versus actual vessel tracks.
- Achieved **25 km RMSE** and **76.6% mean trajectory coverage** for 12-hour vessel trajectory forecasting.
- Deployed the vessel trajectory forecasting model to support **real-time or near-real-time trajectory forecasting**, enabling downstream use in marine traffic analysis and vessel-whale collision risk mitigation workflows.
- Developed **FastAPI endpoints** that returned 12-hour forecasted vessel trajectories and vessel information, including MMSI/vessel identifier, vessel type, destination, current latitude/longitude, forecast confidence or score, and route/destination grid cell.
- Packaged the forecasting model as a **Python package** and developed batch prediction pipelines for model execution, forecasting, and downstream integration.
- Detected abnormal vessel routes by comparing AIS paths against historical route patterns, clustering trajectories to identify outliers, and checking deviations from expected route polygons.
- Supported **North Atlantic Right Whale protection** by developing vessel trajectory forecasting workflows that could support route/speed intervention planning and marine traffic risk analysis.
- Analyzed **VMS fishing-vessel data, ocean-weather variables, and fish-market landing data** to construct semantic trajectories and forecast monthly catch-per-unit effort in the Adriatic Sea.
- Engineered semantic trajectory features from vessel locations, fishing activity labels, month/season indicators, salinity, water temperature, pH, wind, current, wave height, chlorophyll, fish species, landing weight, and grid-cell or region-level features.
- Built a **Random Forest** model for monthly catch-per-unit-effort forecasting.
- Improved CPUE forecasting performance using a new semantic trajectory feature set, increasing **Random Forest R² from 0.674 to 0.854** and reducing **RMSE from 0.466 to 0.313**.
- Used **PostgreSQL/PostGIS, CSV, GeoJSON, Shapefiles, NetCDF, cloud storage, and local Linux server storage** to manage AIS trajectories, spatial boundaries, route polygons, weather/ocean variables, model inputs, and forecasting outputs.
- Created AIS vessel trajectory maps, route-density maps, predicted-vs.-actual trajectory plots, model error charts by forecast hour, vessel-type statistics tables, fishing/catch-per-unit-effort charts, technical reports, research paper figures, and stakeholder presentations.
- Supported development and production environments by deploying Dockerized applications, deploying FastAPI services, and configuring scheduled batch jobs/cron jobs for model execution, data processing, and forecasting workflows.
- Configured **GitHub Actions CI/CD workflows** to run test cases, validate Python package code, automate package build/release workflows, support deployment workflows, and run scheduled model/data pipeline checks.
- Delivered technical reports, API/model documentation, and end-user documentation explaining model workflow, forecasting outputs, deployment logic, and research outcomes.
- Collaborated with machine learning scientists, project managers, government/industry stakeholders, academic supervisors, and research students to develop, deploy, and document maritime analytics and vessel forecasting workflows.
- Contributed to **2 research journal publications** related to maritime tracking data analysis, AISdb integration, and long-term vessel trajectory forecasting.

**Technologies:** Python, Pandas, NumPy, Scikit-learn, PyTorch, TensorFlow, GeoPandas, Shapely, SciPy KDTree, FastAPI, Docker, PostgreSQL, PostGIS, Matplotlib, Plotly, Jupyter, QGIS, Linux server, GitHub Actions, AIS, VMS, NetCDF, GeoJSON, Shapefiles.

---

### University of Electronic Science and Technology of China | Chengdu, China

**Research Scientist | NLP Scientist**  
**09/2018 – 12/2021**

- Conducted academic NLP research and applied ML/NLP system development focused on **short-text classification, short-text clustering, text-stream mining, concept drift detection, evolving data streams, fake review detection, topic modeling, NLP embeddings, anomaly detection in text streams, and high-dimensional text representation**.
- Worked with English short-text batch datasets containing **thousands of records across approximately 250 topics**, including social media posts, news headlines, short messages, and microblogs.
- Developed statistical and machine learning models for evolving short-text classification, improving text-stream classification/clustering performance by up to **20%** compared with baseline TF-IDF and older clustering/classification methods.
- Applied **TF-IDF, BERT, LDA topic modeling, dimensionality reduction, and drift-detection algorithms** for short-text classification, clustering, topic modeling, and evolving text-stream analysis.
- Developed NLP representation techniques by reducing sparse TF-IDF dimensionality, designing topic-based features, improving similarity measurement between short texts, and creating embedding strategies for evolving text streams.
- Detected concept drift in evolving short-text streams by identifying newly emerging topics, topic-distribution changes, and shifts in word usage or vocabulary over time.
- Developed fake-review detection approaches using product reviews, hotel/restaurant reviews, reviewer behavior features, and sentiment/topic-based features to identify deceptive or suspicious short-text reviews.
- Evaluated NLP classification and clustering models using **accuracy, clustering purity, normalized mutual information (NMI), and confusion matrices**, comparing results across baseline and proposed short-text representation methods.
- Improved short-text clustering purity by **10%** through enhanced representation learning, dimensionality reduction, topic-based features, and improved similarity measurement.
- Published **5 research publications** in conference and journal venues and contributed to end-to-end publication workflows.
- Led and supported research publication work by designing experiments, implementing NLP models, reviewing literature, analyzing results, creating figures and tables, writing methodology sections and full manuscript drafts, responding to reviewer comments, and presenting findings at conferences.
- Supported and secured **$50K in project funding** for the research team and delivered **20+ technical reports and research presentations** for academic and project stakeholders.
- Collaborated with the NLP research team, PhD supervisors, and medical imaging researchers on short-text mining, concept drift detection, fake review detection, topic modeling, publication writing, and interdisciplinary AI research.
- Contributed to interdisciplinary medical **3D CT imaging research** through visualization/reporting and research writing support.
- Delivered research papers, Python experiment code, and NLP classification/clustering models for short-text mining, topic modeling, concept drift detection, fake review detection, and evolving text-stream analysis.

**Technologies:** Python, Scikit-learn, TensorFlow, PyTorch, NLTK, spaCy, Gensim, Pandas, NumPy, Matplotlib, Seaborn, Jupyter, SQL, LaTeX, Git, TF-IDF, BERT, LDA, NLP, clustering, classification, topic modeling.

---

### Sapphire Consulting Services | Pakistan

**Software Developer**  
**01/2015 – 05/2015**

- Developed web-based, database-backed enterprise applications for **client/customer management, inventory, and finance workflows**.
- Built Java web application modules using **Java, Spring, Struts 2, JSP, JDBC, MySQL, JavaScript, HTML/CSS, and MVC architecture**.
- Developed and maintained **REST API endpoints** to support enterprise workflow features and database-backed application modules.
- Built and improved modules for **customer profile management, purchase/sales records, invoice generation, payment and finance reporting, search/filtering, and exportable PDF/Excel reports**.
- Designed MySQL database tables, wrote and optimized complex SQL queries, implemented CRUD operations through JDBC, and handled joins across customer, sales, inventory, and payment tables.
- Designed **Jasper Reports** for invoice reporting, including printable and exportable PDF/Excel outputs for finance workflows.
- Fixed bugs and improved existing enterprise application features based on testing feedback and project requirements.
- Used **Subversion SVN** for version control and collaborative software development.
- Delivered assigned Java web application modules **ahead of deadline**, supporting timely client delivery of enterprise customer, inventory, finance, and reporting workflows.
- Collaborated with project managers and QA testers to clarify requirements, validate workflows, resolve bugs, and deliver production-ready modules.

**Technologies:** Java, Spring, Struts 2, JSP, JDBC, MySQL, SQL, Jasper Reports, JavaScript, HTML, CSS, MVC, REST APIs, SVN.

---

### University of Sindh | Jamshoro, Pakistan

**Software Developer Intern**  
**06/2014 – 12/2014**

- Developed Java-based features for **student admission and student management systems**, supporting academic workflow automation and student data processing.
- Built Java desktop application features using **Java Swing**, and supported web application components using **JSP/Servlets, HTML/CSS, and JavaScript**.
- Developed **eligibility and merit-calculation algorithms** to support student admission selection and class/department allocation workflows.
- Built and supported modules for **student profile management, class/department allocation, admission-list generation, fee records, and merit-list preparation**.
- Connected Java applications to **MySQL and Oracle databases** using JDBC.
- Supported database migration between **admission and examination systems**, improving data consistency across academic workflows.
- Created **Jasper Reports** for merit lists and fee reports, supporting printable and structured reporting for admissions and finance-related workflows.
- Improved admission processing speed, reduced manual merit-list preparation, reduced data-entry errors, and supported migration between admission and examination databases.
- Documented user and application workflows to support system handover, maintenance, and staff usage.
- Collaborated with admissions staff, university administrators, senior developers, and database administrators to validate eligibility workflows, improve reporting, and support database-backed system development.

**Technologies:** Java, Java Swing, JSP/Servlets, JDBC, MySQL, Oracle, SQL, HTML, CSS, JavaScript, NetBeans, Eclipse, Jasper Reports, Git/SVN.

---

## Selected Projects

### New York Taxi Data Analytics Dashboard

**Data Engineering Project | Spark/PySpark ETL | Analytics Dashboard**

- Built an end-to-end **New York Taxi analytics dashboard** to analyze taxi trip patterns, process large-scale trip data, and visualize key trip metrics.
- Developed a **Spark/PySpark ETL pipeline** to ingest NYC taxi trip data, clean missing or invalid records, transform pickup/dropoff timestamps, and prepare data for scalable analytics.
- Calculated trip analytics including **trip duration, fare metrics, distance metrics, hourly trends, daily trends, total trips, total fare, average fare, average trip distance, and average trip duration**.
- Partitioned taxi trip data by **date/month** to support efficient processing and scalable reporting.
- Practiced **Dockerized data engineering workflows** using Docker and Docker Compose for reproducible project setup and execution.
- Used **Parquet-based storage patterns** to support structured, columnar analytics workflows.
- Created a **Streamlit analytics dashboard** showing total trips, total fare, average fare, average trip distance, and average trip duration.
- Used **FastAPI** components to support data access and analytics-serving workflows.
- Improved hands-on experience with **Spark/PySpark**, reusable ETL pipeline design, Dockerized workflows, partitioning, and Parquet-based storage patterns.

**Technologies:** Python, Spark, PySpark, Docker, Docker Compose, Streamlit, FastAPI, Pandas, Parquet, GitHub, Jupyter.

---

### GCP Data Engineering and ML Pipeline for Racing Tournament Analytics

- Built an end-to-end cloud data engineering and analytics pipeline using **BigQuery, Bigtable, Looker, Vertex AI, Cloud Storage, Dataflow, Pub/Sub, Python, and SQL**.
- Ingested, cleaned, transformed, and loaded racing/tournament data into **BigQuery**.
- Designed **BigQuery tables/views**, created scheduled queries, stored large-scale data in **Bigtable**, and built **Looker dashboards**.
- Used **Vertex AI** to train/test ML models as part of the cloud analytics workflow.

**Technologies:** BigQuery, Bigtable, Looker, Vertex AI, Cloud Storage, Dataflow, Pub/Sub, Python, SQL.

---

### Fake Short-Text Reviews Detection

**Master’s Research Project**

- Developed a fake-review detection model focused on identifying deceptive reviews using **behavioral and contextual features** from real-life Yelp restaurant and hotel review datasets.
- Cleaned and preprocessed short review text for supervised fake-review classification.
- Engineered behavioral and contextual features including **reviewer deviation**, reviewer content similarity, useful/cool/funny counts, friend count, review count, average posting rate, sentiment/positive ratio, membership length, review duration, and positive-to-negative ratio.
- Implemented **Random Forest and SVM** classifiers to classify reviews as fake or non-fake.
- Compared term-weighting schemes including **NNC, LTC, and BM25** for reviewer-content similarity, with BM25 outperforming the other weighting schemes.
- Evaluated models using **accuracy, precision, recall, F1-score, and 10-fold cross-validation**.
- Improved fake-review classification accuracy/recall by engineering behavioral and contextual features and identifying **reviewer deviation** as an important feature for suspicious review behavior.
- Produced thesis/research-paper outputs including charts, tables, experiment results, and written analysis.

**Technologies:** Python, Scikit-learn, Pandas, NumPy, NLTK, Matplotlib, SQL, Jupyter, Weka, Random Forest, SVM, BM25.

---

### Short-Text Clustering and Classification for Data Streams

**Connected to UESTC PhD Research**

- Researched **evolving short-text stream mining** for sparse, high-dimensional, and changing text data.
- Developed models for **short-text stream clustering, evolving topic detection, concept drift handling, and semi-supervised multi-label classification**.
- Improved handling of **concept drift, evolving topics, sparse short texts, high-dimensional text representation, and limited labeled data**.
- Created semantic-enhanced approaches using word co-occurrence, contextual semantic information, Dirichlet/probabilistic modeling, and decay-based mechanisms for outdated clusters.
- Reduced sparse/high-dimensional semantic feature space using window-based co-occurrence modeling and term-specific weighting.
- Achieved **94.1% average clustering homogeneity** using an online semantic-enhanced Dirichlet model.
- Achieved **1.5% average NMI improvement** through semantic feature reduction and episodic inference methods.
- Compared proposed models against **11 state-of-the-art algorithms on 9 datasets** in terms of classification performance, runtime, and memory consumption.
- Evaluated clustering/classification models using metrics such as **purity, homogeneity, NMI, V-measure, accuracy, runtime, and memory usage**.

**Technologies:** Python, Scikit-learn, NumPy, Pandas, NLTK, Gensim, TensorFlow, PyTorch, Matplotlib, Jupyter, LaTeX, Git.

---

### Pathology Lab Reporting System

- Built a **PHP/MySQL pathology lab reporting system** to manage patient lab reports, automate pathology report generation, track lab test records, support doctor/patient reporting workflows, create printable reports, and manage test categories and results.
- Developed modules for patient registration, lab test category management, test result entry, printable pathology reports, patient/test record search, billing/payment records, user login/role management, and report history tracking.
- Delivered a client-facing system that made lab reports easier to print and share, improved searchability of patient history, and supported clinic/lab staff workflows for test tracking, reporting, and billing.

**Technologies:** PHP, MySQL.

---

### Student Management System / Student Admission System

**University of Sindh Internship / Bachelor’s Project**

- Developed Java-based student admission and management features for academic workflow automation.
- Built modules for merit/eligibility calculation, student profile management, class/department allocation, admission-list generation, fee records, merit lists, fee reports, and database migration between admission and examination systems.
- Improved admission processing speed, reduced manual merit-list preparation, reduced data-entry errors, and supported academic database migration workflows.

**Technologies:** Java, Java Swing, JSP/Servlets, JDBC, MySQL, Oracle, SQL, Jasper Reports.

---

## Education

### Ph.D. in Computer Science

**University of Electronic Science and Technology of China | Chengdu, China**  
**Sep 2018 – Dec 2021**  
Research Focus: **Short-Text Clustering and Classification for Data Streams**

### Master’s in Computer Science

**Quaid-i-Azam University | Islamabad, Pakistan**  
**Jun 2015 – Apr 2018**  
Research Focus: **Fake Short-Text Reviews Detection**

### Bachelor’s in Computer Science

**University of Sindh | Jamshoro, Pakistan**  
**Jan 2011 – Dec 2014**  
Final-Year Project: **Student Management System**

---

## Certifications & Training

### Cloud, Data Engineering & Big Data

- AWS Cloud Practitioner Essential Training
- Google Cloud Foundation
- Data Engineering, Big Data, and Machine Learning on Google Cloud Platform
- Build Batch Data Pipelines on Google Cloud
- Build Data Lakes and Data Warehouses on Google Cloud
- Hadoop

### MLOps & Databricks

- MLOps with Azure Databricks

### Visualization & Reporting

- Data Visualization with Tableau

### API & Software Development

- Designing REST APIs
- Java Technology, Netlync Research Lab

---

## Publications & Research Outputs

- Published **5 research publications** in conference and journal venues related to NLP, short-text mining, text-stream clustering/classification, and evolving data streams.
- Contributed to **2 research journal publications** related to maritime tracking data analysis, AISdb integration, and long-term vessel trajectory forecasting.
- Delivered **20+ research reports and presentations** for academic, technical, and stakeholder audiences.
- Supported and secured **$50K project funding** for research-team activities.
- Contributed to interdisciplinary research involving **medical 3D CT imaging** through visualization/reporting and research writing support.



