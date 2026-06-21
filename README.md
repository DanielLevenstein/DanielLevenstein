# Data Engineer & Cloud Developer

Software engineer with 6+ years of experience working in AWS environments and data systems. Recently focused on machine learning and data analysis projects, including clustering, and business analytics.

🔗 [Deployed Models](https://huggingface.co/DanielLevenstein)
🔗 [Kaggle Notebooks](https://www.kaggle.com/daniellevenstein)

## Professional Work:

- Developed Java/Scala scripts to migrate and normalize legacy financial records into updated schema formats for downstream validation workflows. (FINRA)
- Built a Lambda-based system to track application uptime and system health signals. (b.well)

## Certifications:

- Certified AWS Cloud Practitioner (AWS, 2025)
- Post-Graduate Certificate in Artificial Intelligence & Machine Learning (UT, 2026)

## Featured Projects:
[Featured_Projects](charts/Featured_Projects.png)
*Figure: Shows an image of my AWS Rag and AWS Certification coach project side by side.*

🎓 AWS Certification Coach (ML Evaluation, Streamlit, Docker)<br>
🔗 GitHub: [DaielLevenstein/AWS-Certification-Coach](https://github.com/DanielLevenstein/AWS-Certification-Coach)<br>
🔗 Live Demo: [aws-certification-coach-onrender](https://aws-certification-coach-latest.onrender.com/)

**Overview:** Developed an AI-powered study application for AWS certification practice. The app presents freeform AWS exam-style questions, evaluates learner answers with a trained local classifier, and returns structured coaching feedback with score, missing concepts, detailed answer guidance, and original multiple-choice provenance.

**Key Features:**

- Built a Streamlit study interface for answering AWS certification questions in freeform text.
- Generated self-authored AWS exam-style training, holdout, and sample question datasets.
- Designed a combined JSON artifact format that stores questions, original multiple-choice provenance, correct answers, wrong answers, and partial-credit examples together.
- Trained a local answer classifier to evaluate full-answer correctness with release metrics for accuracy, precision, recall, and confusion matrix results.
- Created a partial-credit regression model using continuous answer ratings and mean-squared error evaluation.
- Added validation tests for classifier behavior, low-credit answer rejection, memory overhead, generated artifacts, and model performance.
- Containerized the application with Docker for local deployment and Render-ready hosting.

**Tools & Technologies:** Python, Streamlit, Docker, Machine Learning, Classification Models, Regression Models, JSON Data Pipelines, Automated Testing, AWS Certification Content

---

### 🎺 AWS Documentation RAG System (LLM, Vector Search, ETL Pipeline)

🔗 [GitHub: Aws-Documentation-Rag](https://github.com/DanielLevenstein/aws-documentation-rag)

**Overview:**
Developed a retrieval-augmented generation (RAG) application for querying AWS documentation. Built a pipeline for crawling AWS documentation pages, preprocessing and storing data in a vector database, and generating technical responses using a language model through a Streamlit interface.

**Key Features:**

- Developed a web crawler for ingesting AWS documentation pages.
- Kept track of feature downloads and crawl depth to prevent redownloading files repeatedly.
- Implemented vector-based semantic retrieval for documentation search workflows.
- Integrated a language model for context-aware technical question answering.
- Built a Streamlit frontend for interactive querying and response generation.
- Containerized the application using Docker for local deployment and testing.

Tools & Technologies: Python, Streamlit, Docker, Vector Databases, LLMs, Web Scraping, ETL Pipelines

---

### 🪖 Helmet Classification Pipeline (CNN, Training Data Curation)

🔗 [Interactive Streamlit App](https://huggingface.co/spaces/DanielLevenstein/Helmet_CNN_Data_Quality_Case_Study)<br>
🔗 [Helmet CNN Training Notebooks](https://github.com/DanielLevenstein/Helmet_CNN_Model_Training_Notebooks)

**Overview:**
Developed an image classification pipeline for helmet detection using a CNN trained on standardized 100x100 image inputs. Build a data curation workflow to transform raw annotation images into standardized size and remove samples with too low a resolution to be useful.

**Key Feature:**

- Built four CNN-based image classification models using four different training datasets.
- Evaluated models based on a holdout dataset consisted of equal numbers of samples from Dataset2, and Dataset3.
- Improved accuracy of a classification model from 77% to 94%, and calculated precision, recal, and f1 metrics for each model.
- Identified categories of images model struggles with for further fine-tuning.

Tools & Technologies: TensorFlow, Keras, OpenCV, Streamlit, HuggingFace

---

### 🍕 FoodHub – Delivery Data Analysis

🔗 [GitHub: FoodHub Data Analysis](https://github.com/DanielLevenstein/FoodHub_UT_ML_Project1)

**Overview:**
Developed discount program for a food delivery app, which reaches up to 12% of the population under model conditions.

**Key Features:**

- Cleaned dataset and imputed missing ratings.
- Identified top-rated restaurants by cuisine.
- Calculated discount cost vs. total customer reach.

![Discount Cost vs Population Reach](charts/Discount_Cost_vs_Total_Reach.png)

*Figure: Discount cost vs total reach with value per customer analysis.*

---

### 💪 Stress vs. Physical Activity – Kaggle Data Analysis

🔗 [Kaggle: Stress vs Physical Activity Correlation](https://www.kaggle.com/code/daniellevenstein/stress-vs-physical-activity-correlation)

**Overview:**
Analyzed relationships between stress levels and physical activity using real-world survey data.

**Key Features:**

- Performed exploratory data analysis and correlation studies
- Generated three population clusters using K-Means
- Identified occupation-based stress correlations
- Visualized cluster separation and activity distribution

![Clustering Overview](charts/Stress_Level_by_Cluster_Side_by_Side.png)

*Figure: K-means clustering reveals distinct population-level groups based on total activity and stress.*

## 📫 Contact

Phone: 512-885-5925
LinkedIn: https://www.linkedin.com/in/daniel-aaron-levenstein/
