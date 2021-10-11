1. Overview
The purpose of this analysis was to remove the speculated dishonest grades from the file and analyze the data based on the confirmed honest grades. To do so we removed the Thomas High School Grade 9 grades (as these were speculated to be dishonest) and analyzed the remaining data.
We then further analyzed the data to see the Scores by: School Type, Grade, School Spending and School Spending.

2. Results
All information for the updated code can be found in the file: PyCitySchools_Challenge_starter_code
-How is the district summary affected?
The district summary is affected as there is a decrease in the new % Overall Passing by 0.2%. Additionally the Average Reading Score appears to have increased by 0.1%.

-How is the school summary affected?
AS you can see from the charts below, when the Thomas High School 9th Grade marks are removed from the data set, the summary for Thomas High School is affected. Below the charts is a summary of all the changes.

With Thomas HS 9th Graders
				School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Thomas High School		Charter		1635		$1,043,130		$638.0			83.42			83.85			93.27		97.31			90.95


Without Thomas HS 9th Graders	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Thomas High School		Charter		1635		$1,043,130.00		$638.00			83.35			83.90			66.91		69.66			65.08

Column			% change from With to Without Thomas HS 9th Graders
Avg. Math Score		-0.07%
Avg. Reading Score	+0.05%
% Passing Math		-26.36%
% Passing Reading 	-27.65%
% Overall Passing	-25.87%

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The per school average for Thomas High school changed when the 9th Grade students were removed. As you can see from the figures below the Average Math Score average increased by 0.05% and the Average Reading score fell by 0.07%.

With 9th Grade Students: 	   Reading Score: 83.85% | Math Score: 83.42%	
Without 9th Grade Students: Reading Score: 83.90% | Math Score: 83.35%

-Scores by school spending:
As Thomas High School falls into the $630-644 bucket that was the only Average score per spending range that was affected.
As you can see from the data below in the $630-644 section, without Thomas High School's 9th Graders the Average Reading Score increased by 0.02% and it decreased in the Average Math Score by 0.02%.

With Thomas High School's 9th Graders
		Avg. Math	Avg. Reading
<$584		83.46		83.93	
$585-629		81.90		83.16	
$630-644		78.52		81.62
$645-675		77.00		81.03


Without Thomas High School's 9th Graders
		Avg. Math	Avg. Reading
<$584		83.46		83.93
$585-629		81.90		83.16
$630-644		78.50		81.64
$645-675		77.00		81.03

-Scores by School size
As Thomas High School falls in the Medium (1000-2000) category this bucket was affected. As you can see from the data below the Medium Bucket's Math Scores without Thomas High School's 9th graders were 0.01% lower and the Reading Scores were 0.01% higher.

Scores with Thomas High School 9th Graders
School Size	     Reading Avg.	Math Avg.
Small (<1000)         83.93		83.82
Medium (1000-2000)    83.86		83.37
Large (2000-5000)     81.34		77.75

Scores without Thomas High school 9th Graders
School Size	     Reading Avg.	Math Avg.
Small (<1000)         83.93		83.82		
Medium (1000-2000)    83.87		83.36		
Large (2000-5000)     81.34		77.75


-Before the 9th grade data was removed the passing percentages at Thomas High School were:
Reading: 97.31%
Math: 93.27%

After the 9th Graders were removed the passing percentages at Thomas High School were (Difference between before and after in brackets):
Reading: 69.66% (-27.65%)
Math: 93.19% (-0.08%)

3. Summary
1. The Passing percentage for math and reading at Thomas High School changed when the 9th Grade students were removed from the data.
2. Changes to the district statistics. There were a few columns that changed slightly when the 9th grade students from Thomas High School were removed from the data.
3. The per school average for Thomas High school changed when the 9th Grade students were removed. As you can see from the figures below the Average Math Score average increased by 0.05% and the Average Reading score fell by 0.07%.

With 9th Grade Students: 	   Reading Score: 83.85% | Math Score: 83.42%	
Without 9th Grade Students: Reading Score: 83.90% | Math Score: 83.35%

4. The Average Reading and Math Scores for 9th Graders across all schools were impacted by removing the 9th grade data from Thomas High School.
Below shows the effects from before Thomas High School's 9th graders were removed and then after they were removed. As you can see the Math scores average dropped by 0.2% and the Reading Score average fell by 0.07%.

Before: Reading Score: 81.91% |	Math Score: 78.94%
After: Reading Score: 81.84%  |	Math Score: 78.74%