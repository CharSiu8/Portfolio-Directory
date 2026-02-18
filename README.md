## Portfolio-Directory

## Hello there, welcome to my Github. 
Here is a list of repos and their descriptions so you can find what you are looking for.

All employers and recruiters are permitted by licensing to run and test code.

## AI Engineering 

**Delta Dental AI Assistant v2:**

https://github.com/CharSiu8/delta-dental-assistant

Try it now: https://delta-dental-app.whitemushroom-7c468829.canadaeast.azurecontainerapps.io/

Multi-agent dental insurance assistant built on Azure AI Foundry/ VS COde with MS SDKs— ask about coverage, find providers, estimate costs in one query
5 specialized agents (Router, Coverage, Provider Finder, Cost Estimator, Orchestrator) with parallel execution and agent chaining
RAG pipeline: Azure AI Search with hybrid vector search across 5 Michigan Delta Dental plan documents
160+ providers across 11 Michigan cities, 53 procedures with dual PPO/Premier cost estimates
Deployed on Azure Container Apps — Streamlit UI, Docker containerized, full Azure cloud pipeline

**DevDocs-AI:**

https://github.com/CharSiu8/DevDocs-AI

Try it now: charsiu8-devdocs-ai.hf.space


- Production RAG system for querying FastAPI docs. Semantic search + GPT-4o-mini answers with source citations.
- Built from scratch — no LangChain.
- Deployed on HuggingFace

**VaultLens:**

https://github.com/CharSiu8/Vault_Lens

- AI Engineering solution for initial DATASCIENCE analysis (EDA)
- privacy first, users can load and run private datasets locally
- automates data profiling, quality assessment, and preliminary analysis
- ollama has a "lens" into the "vault" of data. the model can see the data, but never touches it
  
**BatVision:**

https://github.com/CharSiu8/BatVision

Try it now: https://huggingface.co/spaces/CharSiu8/BatVision
Also deployed on Azure: http://batvision.a4dyasbea5bxc7gd.canadaeast.azurecontainer.io:8000/

* AI image classifier identifying Batman actors (Affleck, Bale, Pattinson) and masked lookalikes (Nite Owl, Darkwing)
* Azure-integrated: Custom Vision (model), Blob Storage (images), full cloud pipeline
* Trained on mask-heavy images — model learns subtle facial features, not just costumes

**GRAYSON:**

This is the updated version of the system because it better fit the client's needs

https://github.com/CharSiu8/GRAYSON

Try it now: https://grayson-7um6.onrender.com

GRAYSON provides intelligent research assistance through:

- AI-curated book recommendations from scholarly works
- Direct uOttawa OMNI library access for every source
- Free PDF discovery when available
- Smart citation extraction from LLM-generated answers
- "Have you considered?" prompts for deeper research directions
- Deployed on Render

**Delta Dental AI Assistant v1**

AI-powered chatbot that answers questions about Delta Dental insurance plans using RAG (Retrieval-Augmented Generation).

https://github.com/CharSiu8/Agenic_RAG_POC-delta-dental

Live Demo: https://huggingface.co/spaces/CharSiu8/delta-dental-assistant

AI-powered chatbot that answers questions about Delta Dental insurance plans using RAG (Retrieval-Augmented Generation).

- Plan Q&A — Ask questions about your specific dental plan coverage
- Coverage Percentages — Get accurate coverage rates for procedures
- Multi-Plan Support — Supports Base, Premium, State, and comparison plans
- Source-Filtered Retrieval — Answers come only from your selected plan

6, RAG_Grayson (The origional GRAYSON):

https://github.com/CharSiu8/RAG_Grayson

Phd level Research RAG chat bot 
- delivers direct links to university libraries. 
- offers "have you considered?" recommendations to direct users to correlated research topics and questions.

## Data Science & Machine Learning

1, Random Forest Classifier, XGB, GridSearch =  RandomForst Classifiers to XGBoost to GridSearchCV = Precision: 83% - Recall: 79% - F1: 81% - Accuracy:  93%

https://github.com/CharSiu8/LoanDefault-Prediction

**Home Equity Loan Default Prediction with XGBoost:**
https://github.com/[your-username]/loan-default-prediction
- A binary classification project to predict loan defaults for INN Hotels Group's home equity lending portfolio, addressing class imbalance (80/20 split) and achieving 93% accuracy with an interpretable XGBoost model.
- This project demonstrates end-to-end classification workflow:
    - Exploratory Data Analysis: Discovered missing debt-to-income disclosure as strongest predictor (62% default rate vs 9%), created strategic missing indicator features, and analyzed credit history patterns across 5,960 loan applications.
    - Feature Engineering & Imputation: Handled 21% missing DEBTINC values by creating indicator columns that preserved predictive signal, performed correlation analysis to identify multicollinearity, and one-hot encoded categorical features with dummy_na=True for missing job/reason data.
    - Model Optimization: Progressed from overfitted Random Forest (100% train, 70% test F1) through hyperparameter tuning to final GridSearchCV-optimized XGBoost achieving 81% F1 score with 83% precision and 79% recall, balancing false positive reduction with default detection for regulatory compliance.
      
2, Insurance Claims Prediction with Logistic Regression:

https://github.com/CharSiu8/insurance-claims-prediction-logistic-regression

- A logistic regression project comparing manual implementation with sklearn industry-standard workflow to predict whether car insurance customers will make a claim.
- This project demonstrates two approaches to logistic regression modeling:
    - Simple Solution: Blindly loops through features using statsmodels' logit function, then manually calculates accuracy using confusion matrix         values (TP, TN, FP, FN).
    - Analytical Workflow Solution: Industry-standard approach with proper pre-processing, visualization, correlation heatmapping to pre-screen           features, and sklearn validation.

3, SuperKart Sales Forecasting with Linear Regression:

https://github.com/CharSiu8/ML_LinearRegression_SuperKart

- A sales forecasting project using linear regression to predict quarterly revenue across SuperKart's 4-store grocery chain, with comprehensive EDA revealing tier-based pricing strategies and product mix optimization opportunities.
- This project demonstrates end-to-end regression modeling workflow:
    - Exploratory Data Analysis: Analyzed 8,763 product records across store types, locations, and tiers to identify revenue drivers and customer preferences (low-sugar products = 73% of sales).
    - Feature Engineering & VIF Analysis: Created derived features (Store_Age_Years, Product_Type_Category), applied get_dummies encoding, and used Variance Inflation Factor to eliminate multicollinear store features, reducing from 17 to 3 predictive features.
    - Model Validation: Built statsmodels OLS regression achieving 77.4% test R², validated with cross-validation, residual analysis, and heteroscedasticity testing to confirm model assumptions and reliability.


4, Random Forests Attrition Prediction Case Study

https://github.com/CharSiu8/RandomForestAttritionPrediction

The tuned Random Forest model achieved 83% recall for predicting employee attrition, with overtime, monthly income, daily rate, number of companies worked, and work experience identified as the strongest drivers. To reduce attrition, the company should minimize overtime through better work management or provide additional compensation, ensure competitive salaries and more frequent promotions with revised stock option plans, and reconsider hiring policies for candidates with excessive job-hopping history. Addressing commute challenges through cab facilities for distant employees, improving workplace culture, and providing better support for junior employees will create a healthier work environment. Special attention should be given to sales and marketing departments with high attrition rates by revising their incentive structures to improve retention.

 
5, FoodHub Delivery Analysis (EDA): 

https://github.com/CharSiu8/foodhub-delivery-analytics

- A comprehensive exploratory data analysis of food delivery order patterns to identify demand trends and revenue optimization opportunities. 
- This project delivers actionable business recommendations backed by statistical analysis and data visualization.

6, UBER analysis (EDA): 

https://github.com/CharSiu8/UBER-Analysis

- extract actionable insights from demand patterns to help the business understand its demand profile and drive better outcomes.

## AI Automation
Please visit my google drive portfolio to see presentations on AI Automation projects - https://drive.google.com/drive/folders/1sd5nk7UbHoA2wwQnIx6VDx9--Ek1iGOP?usp=drive_link

Applicant Tracking System (ATS):

https://docs.google.com/presentation/d/1ao3Lm8Mf2C0Z2dzCUYLVoyvvRMGho-AeKrWG_5CKdQ8/edit?usp=drive_link

Monday Morning: 

https://github.com/CharSiu8/n8nMondayMorning

- Automated n8n workflow that monitors e-commerce sales data and sends intelligent alerts when week-over-week revenue drops by 10%+.
- Uses GPT-4 to generate human-readable incident reports from raw sales metrics.
- Notifies staff/clients in the case of WoW changes
