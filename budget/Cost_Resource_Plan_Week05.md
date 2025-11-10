# Resources Identification

| WBS ID  | Task                              | Resource Type             | Resource Name                                          | Quantity / Hours | Description                                                        |
| ------- | --------------------------------- | ------------------------- | ------------------------------------------------------ | ---------------- | ------------------------------------------------------------------ |
| **1.1** | Define Project Concept            | Human                     | Ahmad Mirza, Fariz, Aqem, Khoo                         | 8 hrs            | Brainstorming and drafting project concept document.               |
| **1.2** | Requirement Gathering             | Human                     | Fariz, Aqem, Ahmad Mirza, Khoo                         | 10 hrs           | Gathering and documenting user and system requirements.            |
| **1.3** | Create Workflow Diagram           | Human, Software           | Ahmad Mirza; Draw.io                      | 4 hrs            | Designing the system workflow diagram using diagramming tools.     |
| **2.1** | Define Roles and Responsibilities | Human                     | Khoo                                                   | 3 hrs            | Assigning roles and defining team responsibilities.                |
| **2.2** | Develop Project Plan              | Human, Software           | Ahmad Mirza, Aqem, Fariz, Khoo; MS Project, Google Sheets    | 6 hrs            | Developing timeline, milestones, and deliverables in project plan. |
| **3.1** | Identify Dataset                  | Human, Software           | Fariz; Kaggle                       | 5 hrs            | Searching, downloading, and storing suitable datasets.             |
| **3.2** | Data Cleaning                     | Human, Software           | Aqem; Python (Pandas), Jupyter Notebook                | 8 hrs            | Cleaning and organizing raw data for analysis.                     |
| **3.3** | Text Preprocessing                | Human, Software           | Ahmad Mirza; Python (NLTK, Regex)                            | 6 hrs            | Removing noise, tokenizing, and preparing text data.               |
| **4.1** | Feature Extraction                | Human, Software           | Khoo; Python (TF-IDF, Scikit-learn)                    | 6 hrs            | Extracting key features from text data for model training.         |
| **4.2** | Model Training                    | Human, Software, Hardware | Fariz; Python (TensorFlow), Scikit-learn, Google Colab | 10 hrs           | Training machine learning model using available hardware.          |
| **4.3** | Model Evaluation                  | Human, Software           | Aqem; Python (Matplotlib), Jupyter Notebook            | 5 hrs            | Evaluating model performance using metrics and charts.             |
| **5.1** | Build Prototype Interface         | Human, Software           | Khoo; Figma, Flutter                                   | 12 hrs           | Designing and developing the prototype user interface.             |
| **5.2** | Integrate Model                   | Human, Software           | Ahmad Mirza; Flask API, Flutter                              | 10 hrs           | Integrating trained model into the mobile application.             |
| **6.1** | Conduct Testing                   | Human, Software           | Fariz; PyTest, Postman                                 | 8 hrs            | Conducting functional and integration testing.                     |
| **6.2** | Improve Performance               | Human, Software, Hardware | Ahmad Mirza; Python Optimization, GPU, Google Colab          | 8 hrs            | Enhancing model and system performance.                            |
| **7.1** | Prepare Report & Slides           | Human, Software           | Khoo, Ahmad Mirza, Aqem, Fariz; MS Word, PowerPoint          | 10 hrs           | Preparing final project report and presentation slides.            |
| **7.2** | Final Presentation                | Human, Equipment          | Team; Laptop, Projector                                | 4 hrs            | Presenting the final system to evaluators.                         |


# Task Cost Estimation

| Task                            | Hours | Resource Type  | Rate (RM/hr) | Total Cost (RM) |
| ------------------------------- | ----: | -------------- | -----------: | --------------: |
| Define Project Concept          |     8 | Human          |           25 |             200 |
| Requirement Gathering           |    10 | Human          |           25 |             250 |
| Create Workflow Diagram         |     4 | Human          |           25 |             100 |
| Define Roles & Responsibilities |     3 | Human          |           25 |              75 |
| Develop Project Plan            |     6 | Human          |           25 |             150 |
| Identify Dataset                |     5 | Human          |           25 |             125 |
| Data Cleaning                   |     8 | Human          |           25 |             200 |
| Text Preprocessing              |     6 | Human          |           25 |             150 |
| Feature Extraction              |     6 | Human          |           25 |             150 |
| Model Training (GPU)            |    10 | Hardware (GPU) |           10 |             100 |
| Model Evaluation                |     5 | Human          |           25 |             125 |
| Build Prototype Interface       |    12 | Human          |           25 |             300 |
| Integrate Model                 |    10 | Human          |           25 |             250 |
| Conduct Testing                 |     8 | Human          |           25 |             200 |
| Improve Performance             |     8 | Human          |           25 |             200 |
| Prepare Report & Slides         |    10 | Human          |           25 |             250 |
| Final Presentation              |     4 | Human          |           25 |             100 |


# Project Budget Summary
| **Cost Category**          | **Example Items / Tasks**                                                             | **Subtotal (RM)** |
| -------------------------- | ------------------------------------------------------------------------------------- | ----------------: |
| **Human Resources**        | Project concept, requirement gathering, workflow design, testing, documentation, etc. |         **2,825** |
| **Hardware / Cloud**       | GPU instance for model training                                                       |           **100** |
| **Software / Licenses**    | Draw.io, PowerPoint (free/open-source assumed)                                        |             **0** |
| **Communication**          | Online meetings, file sharing (Teams, GitHub, etc.)                                   |             **0** |
| **Total Estimated Budget** |                                                                                       |         **2,925** |

## Integration Notes
After adding the Estimated Cost (RM) column to the schedule and reviewing all project phases:

The Model Development phase (Feature Extraction, Model Training, and Model Evaluation) shows a high cost impact, totaling around RM 950, mainly due to computational time (GPU) and specialized expertise required.

The Documentation & Presentation phase also contributes significantly (~RM 650) because it involves multiple team members working collaboratively to finalize the report and slides.

The cost distribution aligns closely with milestones:
- Early planning (Oct) → low cost (concept, requirements)
- Mid-project (Nov–Dec) → peak cost (model training, evaluation)
- End phase (Jan) → moderate cost (testing, final report)

Resource allocation is balanced across members, but critical tasks like model training and testing must be carefully scheduled to avoid GPU overuse or duplicated effort.

Efficient timing of high-cost resources (e.g., GPU usage only during active training) helps control overall spending.

 