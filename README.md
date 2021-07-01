<h1>Capstone Project - Adult Income</h1>
<h2>1. Introduction</h2>
<p>Various factors determine an adult's income, such as education level, age, gender, and field of work.</p>

<h2>2. Data Collection</h2>
<p>The dataset for this project comes from <a href="https://kaggle.com/wenruliu/adult-income-dataset">Kaggle</a>.</p>

<h2>3. Data Wrangling</h2>
<p>I removed the rows with missing values, shown as question marks, added a new binary column for whether or not the income is greater than $50,000, and removed the columns not needed for the analysis.</p>

<h2>4. Feature Engineering and Preprocessing</h2>
<p>I scaled the data and used one-hot encoding on the categorical variables.</p>

<h2>5. Exploratory Data Analysis</h2>
<p>I calculated the proportions of incomes over $50,000 in each category of education, work class, occupation, marital status, relationship, race, and gender.</p>

<h2>6. Machine Learning</h2>
<p>The random forest entropy model is the best of the models I tried because it showed the highest precision, recall, and F-score. The most important factors were being married in a civil procedure, being a husband, and never being married.</p>

<h2>7. Final Report</h2>
<p>This notebook contains my complete analysis and results.</p>
