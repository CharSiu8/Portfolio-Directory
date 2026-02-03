## Portfolio-Directory

## Hello there, welcome to my Github. 
Here is a list of repos and their descriptions so you can find what you are looking for.

All employers and recruiters are permitted by licensing to run and test code.

## AI Engineering 

1, DevDocs-AI:

https://github.com/CharSiu8/DevDocs-AI

Try it now: charsiu8-devdocs-ai.hf.space


- Production RAG system for querying FastAPI docs. Semantic search + GPT-4o-mini answers with source citations.
- Built from scratch — no LangChain.
- Deployed on HuggingFace

2, VaultLens: 

https://github.com/CharSiu8/Vault_Lens

- AI Engineering solution for initial DATASCIENCE analysis (EDA)
- privacy first, users can load and run private datasets locally
- automates data profiling, quality assessment, and preliminary analysis
- ollama has a "lens" into the "vault" of data. the model can see the data, but never touches it
  
3, BatVision:

https://github.com/CharSiu8/BatVision

Try it now: https://huggingface.co/spaces/CharSiu8/BatVision

* AI image classifier identifying Batman actors (Affleck, Bale, Pattinson) and masked lookalikes (Nite Owl, Darkwing)
* Azure-integrated: Custom Vision (model), Blob Storage (images), full cloud pipeline
* Trained on mask-heavy images — model learns subtle facial features, not just costumes

4, GRAYSON:

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

5, Delta Dental AI Assistant:

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

1, Insurance Claims Prediction with Logistic Regression:

https://github.com/CharSiu8/insurance-claims-prediction-logistic-regression

- A logistic regression project comparing manual implementation with sklearn industry-standard workflow to predict whether car insurance customers will make a claim.
- This project demonstrates two approaches to logistic regression modeling:
    - Simple Solution: Blindly loops through features using statsmodels' logit function, then manually calculates accuracy using confusion matrix         values (TP, TN, FP, FN).
    - Analytical Workflow Solution: Industry-standard approach with proper pre-processing, visualization, correlation heatmapping to pre-screen           features, and sklearn validation.

2, SuperKart Sales Forecasting with Linear Regression:

https://github.com/CharSiu8/ML_LinearRegression_SuperKart

- A sales forecasting project using linear regression to predict quarterly revenue across SuperKart's 4-store grocery chain, with comprehensive EDA revealing tier-based pricing strategies and product mix optimization opportunities.
- This project demonstrates end-to-end regression modeling workflow:
    - Exploratory Data Analysis: Analyzed 8,763 product records across store types, locations, and tiers to identify revenue drivers and customer preferences (low-sugar products = 73% of sales).
    - Feature Engineering & VIF Analysis: Created derived features (Store_Age_Years, Product_Type_Category), applied get_dummies encoding, and used Variance Inflation Factor to eliminate multicollinear store features, reducing from 17 to 3 predictive features.
    - Model Validation: Built statsmodels OLS regression achieving 77.4% test R², validated with cross-validation, residual analysis, and heteroscedasticity testing to confirm model assumptions and reliability.


3, FoodHub Delivery Analysis (EDA): 

https://github.com/CharSiu8/foodhub-delivery-analytics

- A comprehensive exploratory data analysis of food delivery order patterns to identify demand trends and revenue optimization opportunities. 
- This project delivers actionable business recommendations backed by statistical analysis and data visualization.

4, UBER analysis (EDA): 

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
