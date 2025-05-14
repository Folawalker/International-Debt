# International-Debt
This is a work on a dataset that carries the global debt indicators and amounts owed by each country, the source of the loan, purpose, regional disparities in borrowing and access to loans. 
# Table of Content
- Project Overview
- Dataset
- Data Inspection
- Data Cleaning
- Exploratory Data Analysis
  - Overview of the Data
    - Descriptive Statistics
    - Data Type Verification
    - Checking for Duplicates
  - Descriptive Analysis
    - Debt Burden by Country
    - Debt Burden by Continent
    - Average Debt Owed by Continent
    - Biggest Debtor(China)
    - Country of Interest(Nigeria)
    - Debt Domination by Composition
      - Disbursement
      - Interest Payment(Long Term and Private Non Guaranteed)
      - Bilateral Loans
      - Bonds
      - Commercial Bank Loans
      - Multilateral Loans
      - Official Creditors
      - Private Creditors
      - Other Private Creditors
      - Principal Repayment
- Insights
- Strategic Insights
- Contributions

# Project Overview
The main purpose of this analysis is to help gain insights into the world debtors, regional access and willigness to take loans, sources of debts of each country, and much more.

# Dataset
- `Country`: Country in view
- `Country_code`: Global code used to refer to the country in view
- `Indicator_name`: Full name of the debt indicator in view
- `Indicator_code`: Economic code used to refer to the debt indicator in view
- `Debt`: Amount owed by each country under each indicator
- `Continent`: Continent of the country in view
# Data Inspection
Data information was checked using `.info()` function on python and it helped confirm there were no missing values, also confirmed the datatypes, number of rows and columns.

# Data Cleaning
The dataset had been cleaned from excel before importing to python. Then I used a custome 'country_converter' to assign a continent to the countries in the dataset

# Exploratory Data Analysis
## 1. Overview of the Data
### 1. Descriptive Statistics:
Used the `.describe()` function to check the basic statistical distribution of the dataset(mean, median, mode, max and min values, etc..)

### 2. Data Verification:
Checked if the changes I made during the cleaning process from Excel took effect(TRIM, data type, etc..) 

### 3. Checking for Duplicates:
I checked for the presence of duplicates, or rather, the lack thereof.

## 2. Descriptive Analysis
- Debt Burden by Country: Checked for the total amount owed by each country.
- Debt Burden by Continent: Checked for the total amount owed by cotinents.
- Average Debt Owed by Continent: Checked for the average debt owed by countries on each continent.
- Biggest Debtor(China): Checked the debt composition of China, the world's biggest debtor.
- Country of Interest(Nigeria): Checked the debt composition of Nigeria.
- Debt Domination by Composition
      - Disbursement: Checked for the amount of new loans secured by countries and continents.
      - Interest Payment(Long Term and Private Non Guaranteed): Checked for the amount of debts owed by countries and continent is due to interest payment on existing long term loans.
      - Bilateral Loans: Checked for the amount of debt owed to loans granted by single lenders.
      - Bonds: Checked for the amount of debt owed due to private bonds.
      - Commercial Bank Loans: Checked for the amount owed due to loans from commercial banks.
      - Multilateral Loans: Checked for the amount owed dues to loans from World Bank or the IMF.
      - Official Creditors:Checked for the amount owed due to loans from international organisations, governments and government agencies.
      - Private Creditors: Checked for debt owed due to loans gotten from an individual or organization.
      - Other Private Creditors: Checked for debt owed due to loans gotten from hedge funds, asset managers, or commodity traders.
      - Principal Repayment: Checked for debt owed due to repayment of pricipal on existing loans.

# Insights
- Nigeria’s burden comes largely from repaying older loans, not new disbursements.

- China is the world's biggest debtor with $285.8 billion, largely due to principal repayments on long-term foreign loans $96 billion and private non-guaranteed debt $72 billion, Brazil is a close second with $280.6 billion.

- China and Brazil's dominance in the debt figures reflects large-scale international borrowing, possibly linked to massive infrastructure projects and energy investments.

- Other major debtors include South Asia region, UN’s Least Developed Countries, and Russia.

- Sao Tome and Principe has the lowest total debt of $44.8 million.

- Other low-debt countries include Tonga, Comoros, Timor-Leste. These countries are generally small economies with limited borrowing capacity or better debt discipline.

- Asia dominates the global external debt while Oceania does not borrow as much as others.

- South America has the highest average debt per country, approximately $2.4 billion.

- Africa has a lower average, $508 million, despite being 2nd in total showing high country count but smaller individual loans.

- South American countries owe the most money per country with $240 million.

# Strategic Insights
- China is structurally indebted across nearly every loan category. This implies a deliberate economic strategy built on external financing.

- South America, while not highest in total, has the most per-country debt which suggests deeper borrowing per country than other continents.

- Africa appears heavily exposed to official and bilateral debt, which may tie it closely to conditional financing programs.

- Oceania's consistent position at the bottom across every debt type signals either strong fiscal discipline or limited access to capital markets.

- Multilateral loans (World Bank, IMF) play a strong stabilizing role, especially in Africa and Asia.



# Contributions
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.
