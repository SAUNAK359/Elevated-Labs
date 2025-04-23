CUSTOMER PERSONALITY ANALYSIS DATA CLEANING PIPELINE
---------------------------------------------------

1. PROJECT DESCRIPTION
- Cleans and prepares raw customer marketing data from Kaggle
- Transforms dataset into analytics-ready format
- Generates processed files for visualization and modeling

2. PREREQUISITES
- Python 3.8+
- Required packages (see requirements.txt)
- Kaggle account (for data access)

3. FILES INCLUDED
- clean_data.py : Main cleaning script
- requirements.txt : Python dependencies
- /data/input/marketing_campaign.csv : Raw data
- /data/output/cleaned_data.csv : Processed output
- /data/output/cleaned_sample.csv : 1000-row sample

4. DATA TRANSFORMATIONS APPLIED
* Handled missing values in Income
* Standardized:
  - Education categories
  - Marital status labels
* Derived new features:
  - Age from birth year
  - Total children count
  - Family size
* Removed invalid ages (<18 or >100)
* Eliminated duplicate records

5. USAGE INSTRUCTIONS
A) Local execution:
  1. pip install -r requirements.txt
  2. Place raw data in /data/input/
  3. Run clean_data.py
  4. Find results in /data/output/

B) Kaggle execution:
  1. Upload notebook to Kaggle
  2. Attach source dataset
  3. Run all cells
  4. Download outputs from /kaggle/working/

6. OUTPUT FILES
- cleaned_customer_data.csv : Full processed dataset
- cleaned_sample.csv : Verification sample
- processing_log.txt : Transformation audit log

7. CONTACT
For questions or issues, please contact:
saunakdaschaudhuri4@gmail.com
