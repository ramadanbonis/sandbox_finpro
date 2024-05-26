<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Bank Marketing Dataset Analysis and Prediction</h1>
<p>
    This repository contains the analysis and prediction of bank marketing data to determine if a client will subscribe to a term deposit. The dataset is sourced from a marketing campaign by a Portuguese banking institution.
</p>

<h2>Dataset Description</h2>
<p>
    The dataset contains information about clients, their demographics, and details about their interactions with the bank's marketing campaigns. The aim is to predict the likelihood of a client subscribing to a term deposit.
</p>

<h3>Columns Description</h3>
<ul>
    <li><strong>age</strong>: Age of the client (numeric).</li>
    <li><strong>job</strong>: Type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services").</li>
    <li><strong>marital</strong>: Marital status (categorical: "married", "divorced", "single"; note: "divorced" means divorced or widowed).</li>
    <li><strong>education</strong>: Level of education (categorical: "unknown", "secondary", "primary", "tertiary").</li>
    <li><strong>default</strong>: Has credit in default? (binary: "yes", "no").</li>
    <li><strong>balance</strong>: Average yearly balance, in euros (numeric).</li>
    <li><strong>housing</strong>: Has housing loan? (binary: "yes", "no").</li>
    <li><strong>loan</strong>: Has personal loan? (binary: "yes", "no").</li>
    <li><strong>contact</strong>: Contact communication type (categorical: "unknown", "telephone", "cellular").</li>
    <li><strong>day</strong>: Last contact day of the month (numeric).</li>
    <li><strong>month</strong>: Last contact month of year (categorical: "jan", "feb", "mar", "apr", "may", "jun", "jul", "aug", "sep", "oct", "nov", "dec").</li>
    <li><strong>duration</strong>: Last contact duration, in seconds (numeric).</li>
    <li><strong>campaign</strong>: Number of contacts performed during this campaign and for this client (numeric, includes last contact).</li>
    <li><strong>pdays</strong>: Number of days since the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted).</li>
    <li><strong>previous</strong>: Number of contacts performed before this campaign and for this client (numeric).</li>
    <li><strong>poutcome</strong>: Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success").</li>
</ul>

<h3>Target Variable</h3>
<ul>
    <li><strong>y</strong>: Has the client subscribed to a term deposit? (binary: "yes", "no").</li>
</ul>

<h2>Analysis and Machine Learning</h2>
<p>
    The following steps were performed to analyze and build a machine learning model:
</p>

<h3>Exploratory Data Analysis (EDA):</h3>
<ul>
    <li>Understanding data structure, missing values, and distributions.</li>
    <li>Visualizing distributions and relationships.</li>
</ul>

<h3>Data Preprocessing:</h3>
<ul>
    <li>Handling missing values.</li>
    <li>Encoding categorical variables using Label Encoding and One-Hot Encoding.</li>
</ul>

<h3>Creating New Features:</h3>
<ul>
    <li>Ratio of balance to campaign (balance_campaign_ratio).</li>
    <li>Age groups (age_group).</li>
    <li>Contact group.</li>
    <li>Week (convert day to week).</li>
</ul>

</body>
</html>
