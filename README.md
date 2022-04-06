# PyCity_Schools_Challenge
Py  City schools analysis

Purpose 
The purpose of this project is to review the overall performance of the Py City School District high schools to improve individual schools within the district as well as the district overall.  Using comparative metrics, the client wishes to determine if specific schools would benefit from additional support to increase performance rankings. Performance measures are math scores, reading scores, and overall passing percentage, which is the two (math and reading scores) together. Independent variables are size and type of school, that is, the number of students and whether the school is charter or district; the total budget for each school, and the budget per student. The analysis examines the relationship between these variables to see which ones may affect performance.
 
Composition of the District
Py City Schools comprises 15 schools, eight of which are district schools, seven which are charter.  Schools include grades 9 thru 12. Total student population is 39,170 with school size varying from 427 to nearly 5,000.    The total budget for the district is approximately $ 24,650,000.

Issues
The client reports that one school, Thomas High School, is suspected of academic dishonesty in possible alteration of the 9th grade math and reading scores. Accordingly, a second analysis was conducted omitting that data.  This summary briefly compares the two.

Findings

Performance
•	Overall, charter schools performed better than district schools: 
o	Charter averaged 90% overall passing
o	District averaged 54% overall passing
•	Ranked by overall performance, the top five schools are charter schools, and the bottom five are district schools. In fact, charter schools are all ranked ahead of district schools. 
Size
•	Charter schools have smaller student populations
o	Charter schools average about 1,525
o	District average close to 3,850, about 2 ½ times as many
o	There is a strong negative correlation between school size and pass rates: Pass rates for smaller schools is significantly higher than for larger schools
Budget
•	Per capita, district schools on average, spend about 7% more per school per student than charter schools
•	District schools comprise 47% of the total 15 schools, but are apportioned 69% of the budget
•	There is a strong negative correlation between per capita spending and overall rates of passing: district schools have greater budgets, but lower passing rates.  
•	This may be due to higher facility costs for the larger district schools

Effect of Omitted Data
The second analysis was conducted on the original data set with null values for Thomas High School’s ninth grade math and reading score. This analysis did not reveal discrepancies in the results. 

Conclusion
The most significant trend meriting further investigation is the correlation between per capita budget and pass rates.  Doing a cost analysis of the same schools across the board, as conducted here, could be assistive in identifying specific costs, whether fixed or variable, that feed into and form the budgets. Such an analysis could be of benefit in developing an informed and effective strategy to boost performance.  Additionally, outside of the cost metrics, reviewing ratios of instructor to pupil as well as looking closely at soft data such as culture, expectations, and other qualitative inputs could be informative; in essence, I believe conducting social science analyses would be worthwhile.

Py School District Summary by School 


School	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Bailey High School	District	       4,976 	$3,124,928 	$628 	77	81	67%	82%	55%
Cabrera High School	Charter	       1,858 	$1,081,356 	$582 	83	84	94%	97%	91%
Figueroa High School	District	       2,949 	$1,884,411 	$639 	77	81	66%	81%	53%
Ford High School	District	       2,739 	$1,763,916 	$644 	77	81	68%	79%	54%
Griffin High School	Charter	       1,468 	$917,500 	$625 	83	84	93%	97%	91%
Hernandez High School	District	       4,635 	$3,022,020 	$652 	77	81	67%	81%	54%
Holden High School	Charter	          427 	$248,087 	$581 	84	84	93%	96%	89%
Huang High School	District	       2,917 	$1,910,635 	$655 	77	81	66%	81%	54%
Johnson High School	District	       4,761 	$3,094,650 	$650 	77	81	66%	81%	54%
Pena High School	Charter	          962 	$585,858 	$609 	84	84	95%	96%	91%
Rodriguez High School	District	       3,999 	$2,547,363 	$637 	77	81	66%	80%	53%
Shelton High School	Charter	       1,761 	$1,056,600 	$600 	83	84	94%	96%	90%
Thomas High School	Charter	       1,635 	$1,043,130 	$638 	83	84	93%	97%	91%
Wilson High School	Charter	       2,283 	$1,319,574 	$578 	83	84	94%	97%	91%
Wright High School	Charter	       1,800 	$1,049,400 	$583 	84	84	93%	97%	90%
 	 	 	 	 	 	 	 	 	 
Py School District Summary by School 

 	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Totals & Averages	District 7
Charter 8	    39,170 	 $24,649,428 	$620 	79	82	75%	86%	65%

School	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math
Cabrera High School	Charter	             1,858 	 $      1,081,356.00 	 $        582 	83.1	84.0	94%
Thomas High School	Charter	             1,635 	 $      1,043,130.00 	 $        638 	83.4	83.8	93%
Griffin High School	Charter	             1,468 	 $         917,500.00 	 $        625 	83.4	83.8	93%
Wilson High School	Charter	             2,283 	 $      1,319,574.00 	 $        578 	83.3	84.0	94%
Pena High School	Charter	                 962 	 $         585,858.00 	 $        609 	83.8	84.0	95%
Wright High School	Charter	             1,800 	 $      1,049,400.00 	 $        583 	83.7	84.0	93%
Shelton High School	Charter	             1,761 	 $      1,056,600.00 	 $        600 	83.4	83.7	94%
Holden High School	Charter	                 427 	 $         248,087.00 	 $        581 	83.8	83.8	93%
Bailey High School	District	             4,976 	 $      3,124,928.00 	 $        628 	77.0	81.0	67%
Ford High School	District	             2,739 	 $      1,763,916.00 	 $        644 	77.1	80.7	68%
Johnson High School	District	             4,761 	 $      3,094,650.00 	 $        650 	77.1	81.0	66%
Hernandez High School	District	             4,635 	 $      3,022,020.00 	 $        652 	77.3	80.9	67%
Huang High School	District	             2,917 	 $      1,910,635.00 	 $        655 	76.6	81.2	66%
Figueroa High School	District	             2,949 	 $      1,884,411.00 	 $        639 	76.7	81.2	66%
Rodriguez High School	District	             3,999 	 $      2,547,363.00 	 $        637 	76.8	80.7	66%

 	Math Scores	Reading Scores
School	9th	10th	11th	12th	9th	10th	11th	12th
Bailey High School	77	77	78	76	81	81	81	81
Cabrera High School	83	83	83	83	84	84	84	84
Figueroa High School	76	77	77	77	81	81	81	81
Ford High School	77	78	77	76	81	81	80	81
Griffin High School	82	84	84	83	83	84	84	84
Hernandez High School	77	77	77	77	81	81	81	81
Holden High School	84	83	85	83	84	83	84	85
Huang High School	77	76	76	77	81	82	81	80
Johnson High School	77	77	77	77	81	81	81	81
Pena High School	84	83	84	84	84	84	84	85
Rodriguez High School	77	77	76	78	81	81	81	80
Shelton High School	83	83	83	84	84	83	84	83
Thomas High School	84	83	83	83	84	84	84	84
Wilson High School	83	84	83	83	84	84	84	84
Wright High School	83	84	84	84	84	84	84	84
Averages	80	80	81	80	83	83	83	83

