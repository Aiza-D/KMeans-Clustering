<h1>Table of contents</h1>
<ul>
<li>Data Source</li>
<li>Data Attributes</li>
<li>Objective</li>
<li>Task Name</li>
<li>Steps followed</li>
  </ul>
<h1>Categorising countries</h1>
<h2>Data Source</h2>
The data used in this task was orginally sourced from Help.NGO. This international non-governmental organisation specialises in emergency response, preparedness, and risk mitigation.

<h2>Dataset Attributes</h2>
<b>country:</b> Name of the country.<br>
<b>child_mort:</b> Death of children under 5 years of age per 1000 live births.<br>
<b>exports:</b> Exports of goods and services per capita. Given as a percentage of the GDP per capita.<br>
<b>health:</b> Total health spending per capita. Given as a percentage of GDP per capita.<br>
<b>imports:</b> Imports of goods and services per capita. Given as a percentage of the GDP per capita.<br>
<b>income:</b> Net income per person.<br>
<b>inflation:</b> The measurement of the annual growth rate of the Total GDP.<br>
<b>life_expec:</b> The average number of years a new born child would live if the current mortality patterns remain the same.<br>
<b>total_fer:</b> The number of children that would be born to each woman if the current age-fertility rates remains the same.<br>
<b>gdpp:</b> The GDP per capita. Calculated as the Total GDP divided by the total population.<br>
<h2>Objective</h2>
To group countries using socio-economic and health factors to determine the development status of the country.

<h1>KMeans Clustering</h1>
<h2>Steps followed:</h2>
Follow steps have been followed: <br><br>

<ol>
<li>Loading the Country-data.csv dataset. </li>
<li>Dropping any non-numeric columns from the dataset. </li>
<li>Plotting nine different scatter plots with different combinations of variables against GDPP and child_mort. For example, GDPP vs health. </li>
  <ul>
  <li>Note which of these plots looks the most promising for separating into clusters.</li>
  </ul>
<li>Normalising the dataset using MinMaxScaler from sklearn. </li>
<li>Finding the optimal number of clusters using the elbow and silhouette score method. </li>
<li>Fitting the scaled dataset to the optimal number of clusters. Reporting back on the silhouette score of the model. </li>
<li>Visualising the clusters for the following two groups:  </li>
     <ul>
  	<li>Child mortality vs GDPP</li> 
  	<li>Inﬂation vs GDP</li>
     </ul>
<li>Labeling the groups of countries in the plots created based on child mortality, GDPP, and inﬂation using terms such as: </li>
  <ul>least developed, developing, and developed.</ul>
</ul>
