# Hospital Cost Quality

### 1. Goal

To identify the relationship of the cost and the quality of cardiac services in the United States. 

Heart failure and heart attack are two forms of heart disease. They have some common causes. Heart attacks can lead to heart failure by weakening the heart's pumping ability. I will investigate into both heart failure and heart attack treatment and services in this analysis. 

### 2. Description of Datasets

In order identify the relationship of cost and quality, I will need the data of cost/payments and outcome measures. I searched in the CMS database and found several datasets that will help. All of these datasets contains the information of the same hospitals registered at CMS and have similar time frames (except for Timely and Effective Care Dataset). The outcome measures could be found in Unplanned Hospital Visits - Hospital, Complications and Deaths - Hospital, and Timely and Effective Care - Hospital datasets. The corresponding payments data could be found in Payment and Value of Care. Other hospital information could be found in  Hospital General Information. 

* **Hospital General Information** 
    * A list of all Hospitals that have been registered with Medicare. The list includes addresses, phone numbers, and hospital type.
    * \# of Hospitals: 4806
    

* **Payment and Value of Care**
    * Payment: The payment measures add up the payments for care starting the day the patient enters the hospital and continuing for the next 30 days (or 90-day for hip/knee replacement).
    * The death rates look at deaths in the first 30 days after the patient is hospitalized for a heart attack, heart failure, or pneumonia. 
    * Time window: 2013-04-01 to 2016-06-30
    * \# of Hospitals: 4806

    
* **Unplanned Hospital Visits - Hospital**  
    https://www.medicare.gov/hospitalcompare/Data/Hospital-returns.html
    * This data set includes provider data for the hospital return days (or excess days in acute care) measures, the unplanned readmissions measures, and the rate of unplanned hospital visits after an outpatient colonoscopy.
    * The lower score, the better
    * Time window: 2013-07-01 to 2016-12-31
    * \# of Hospitals: 4806
    

* **Complications and Deaths - Hospital**
    *  This data set includes provider data for the hip/knee complication measure, the Agency for Healthcare Research and Quality (AHRQ) measures of serious complications, and 30-day death rates.
    * Time window: 2013-04-01 to 2016-06-30
    * \# of Hospitals: 4806
    
    
* **Timely and Effective Care - Hospital**
    * This data set includes provider-level data for measures of heart attack care, heart failure care, pneumonia care, surgical care, emergency department care, preventive care, children’s asthma care, blood clot prevention and treatment, pregnancy and delivery care, and cancer care.
    * Time window: 2016-01-01 to 2017-03-31
    * \# of Hospitals: 4806

### 3. Data Processing
 3.1 Load Data  
 3.2 Clean Data  
 3.3 Choose Target Variables   
 3.4 Merge Datasets   
 3.5 Rescale Payments   
### 4. Exploratory Data Analysis
 4.1 Distribution of Variables and Measures    
 4.2 Cost and Unplanned Hospital Visits   
 4.3 Cost and 30-Day Mortality Rate   
 4.4 Cost and Timely and Effective Measures  
### 5. Modeling  
 5.1 Simple Linear Regression   
 5.2 Multiple Linear Regression   
### 6. Results and Discussion   
