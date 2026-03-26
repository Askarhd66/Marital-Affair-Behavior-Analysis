<h1>Understanding Drivers of Extra-Marital Affairs</h1>

<h2>Project overview</h2>
<p>
A psychological study collected data on married individuals to understand factors associated
with extra-marital affairs. This project uses logistic regression to model the probability
that a person has an affair based on demographic and relationship-related attributes.
</p>

<h2>Business / research problem</h2>
<p>
Researchers wanted to:
</p>
<ul>
  <li><b>Quantify how different factors</b> (age, years married, satisfaction, etc.) relate to affairs.</li>
  <li><b>Identify significant predictors</b> while controlling for other variables.</li>
  <li><b>Build a classification model</b> that flags higher likelihood of an affair.</li>
</ul>

<h2>Objectives</h2>
<ul>
  <li><b>Convert the affair count variable</b> into a binary indicator (affair vs no affair).</li>
  <li><b>Build a logistic regression model</b> to classify individuals.</li>
  <li><b>Interpret coefficients</b> to understand direction and strength of relationships.</li>
</ul>

<h2>Data and features</h2>
<p>
The dataset includes:
</p>
<ul>
  <li><b>Demographics:</b> age, years married, number of children.</li>
  <li><b>Relationship factors:</b> marital satisfaction, religiousness, education.</li>
  <li><b>Target variable:</b> binary indicator of having an affair or not.</li>
</ul>

<h2>Methodology</h2>
<ul>
  <li><b>Data preprocessing:</b> converting the affair count to binary, handling missing values.</li>
  <li><b>Exploratory analysis:</b> distributions and relationships between features and affair status.</li>
  <li><b>Modeling:</b> logistic regression on scaled data.</li>
  <li><b>Evaluation:</b> confusion matrix, accuracy, ROC curve, and AUC.</li>
</ul>

<h2>Key results</h2>
<ul>
  <li><b>Estimated probabilities</b> of having an affair for each individual.</li>
  <li><b>Significant predictors</b> identified via model coefficients and p-values.</li>
  <li><b>Model performance</b> summarized through ROC-AUC and classification metrics.</li>
</ul>

<h2>Impact</h2>
<ul>
  <li><b>Research insight:</b> better understanding of factors associated with extra-marital affairs.</li>
  <li><b>Policy and counseling:</b> potential guidance for relationship counseling strategies.</li>
</ul>
