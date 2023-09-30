# Project 3 : HR IBM project
<h3> Data Analyst internship from Meriskills : Task03 </h3>
<p>Business Problem :<b> Why employees left our company ? or why the rate of attriaion become higher  ? </b></p>
- we have some steps before going to make a model to solve this problem :
<ol>
<li> Data Collection</li>
<li> Data prepare </li>
<li> Explorate Data Analysis and try discovering some patterns </li>
<li> Data Preprocessing before modeling</li>
<li> Machine learning</li>
<li> Evaluating the Model</li>
<li> Testing Model</li>
<li> solutions</li>
</ol> 

<p>About data : this dataset is about Hr data that try to help company why employees left company so in this data you can find a lot of things that will help Hr to solve this problem</p>

<p> 
<h3>some Corrleations : </h3>
<ol>
 <li> After doing Data collection and Data prepare data is Cleaned
- By using EDA I found some results : first = correlations:</li>
<li>Ages have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ]
o Good : In range [ 0.2 – 0.3 ] with columns ( YearWithCurrentManager , 
YearSinceLastPromotion , YearInCurrentRole , YearsAtCompany , numberCompanyWorked , 
Education ) 
o Strong: in Range [ 0.5 – 0.7] with Columns (TotalWorkingYears, MonthlyIncome, JopLevel) </li>
<li> JopLevel have good or Strong relationship: good [0.2 – 0.4] , strong [ 0.5 – 1.0 ]
o Good : with columns ( YearWithCurrentManager , YearSinceLastPromotion ,
YearInCurrentRole )
o Strong : with columns ( YearsAtCompany , TotalWorkingYears , MonthlyIncome (95%) ) </li>
<li> MonthlyIncome have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ]
o Good : ( YearWithCurrentManager , YearSinceLastPromotion , YearInCurrentRole)
o Strong : with Columns ( YearsAtCompany, TotalWorkingYear ) </li>
<li> PercentSalaryHeky have Strong relationship with PerformaceRating </li>
<li> TotalWorkingYear have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ] </li>
o Good : columns ( YearWithCurrentManager , YearSinceLastPromotion , YearInCurrentRole , 
numberCompanyWorked )
o Strong : with columns ( YearsAtCompany ) </li>
<li> YearsAtCompany : have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ]
o Strong : with columns ( YearWithCurrentManager , YearSinceLastPromotion ,
YearInCurrentRole ) </li>
<li> YearsInCurrentRole : have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ]
o Strong : with Columns (YearWithCurrentManager , YearSinceLastPromotion )  </li>
<li> YearsSinceLastPromotions : have good or Strong relationship : good [0.2 – 0.4 ] , strong [ 0.5 – 1.0 ]
o Strong : with Columns ( YearWithCurrentManager ) </li>
</ol>
******************************************************************************************
<p><b>Business Questions i asked to tring discovering some Insights :</b> <p>
  <ol>
<li> How does the daily rate vary for employees who work overtime compared to those who don't ?
o We found number of employes That Not Worked OverTime Have High Daily Rate by rate : 
71.49% , number employees that have low dailyRate by rate : 28,51%</li>
<li> Do married employees tend to have higher or lower salaries compared to their single or divorced 
counterparts ?
o I found the Married and Divorced employees have the same Rate of monthlyIncome by rate : 
34.9 % , but in single have low of them by rate : 30.2% with difference 4.7%</li>
<li> Does the percentage of salary hike differ for employees with Jop roles and different marital statuses 
?
o No we found SalaryHike Not really differ between JopRoles and marital statuses </li>
<li> How does job satisfaction vary across different job roles ?
o I found the most role have high number of jop satisfactions [ Sales Executive - Research 
scientists ] 
o But we found the average jop satisfactions in all JopRoles was nearly : 2.5 – 3 where the most 
employees give rate 2.5 these mean they have a problem with their JopRoles</li>
<li> Some Notes :
o Some reasons that maybe cause emp left companys [ distanceFromHome , Environment 
Satisfaction , Jop Satisfaction , monthlyIncome , worklifeBalance , YearLastPromotion , 
<li> Remember DataSet isnot Imbalanced as I found more that 1200 emp not left company , the number 
of emp that left company was 200 there are a bias or imbalanced </li>
    </ol>
  </p>
    
<h3>Machine Learning Stage</h3> :
    <ul>
<li> I found my data is not balanced so I used a specific tec to make it balanced by using
( RandomOverFitting )</li>
<li> Now Data is Balanced we want to convert Categorical data to numeric data so we use Labal encoder </li>
<li> After that I use Logistic Regression to classify but I found the Accuracy 80% but is not the best one so 
I used Feature Engineering and used a specific Tec called ( Random Forest Classifier ) this tec help me 
choose the importance features that will make my model better </li>
<li> So after I using it I get a best accuracy ( 1.00 )</li>
</ul>

# Thank You.@


