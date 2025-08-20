# cdsd-jedha-2025-b02-bigdata-steam

Quick EDA of Steam’s videogame marketplace using **Databricks** + **PySpark**, with built-in Databricks visualizations.

## 📦 Dataset
- Source (S3): `s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json`  
- Format: Semi-structured JSON (nested fields)

## 🧰 Tech stack
- Databricks (Community/Workspace)
- PySpark (Spark SQL, `explode`, `getField`, aggregates)
- Databricks visualizations & dashboards

## 🔗 Published Notebooks (public)
- **Steam EDA — Macro Analysis**  
  [View Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3481542937551785/2824557762392942/884345798385328/latest.html)
- **Steam EDA — Genres & Platforms**  
  [View Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3481542937551785/1436402007373042/884345798385328/latest.html)

## 🗂️ What each notebook covers

**1) Macro Analysis**
- Initial imports & schema unnesting
- Publishers with most releases  
- Best-rated games  
- Releases by year (incl. COVID period)  
- Price distribution & discounts  
- Top languages  
- Age restrictions (PEGI-like 16/18)

**2) Genres & Platforms**
- Genre representation 
- Positive vs. negative review ratio by genre  
- Publishers’ preferred genres  
- Most “lucrative” genres   
- Platform coverage (Windows/Mac/Linux)  
- Genre × platform availability patterns
 
