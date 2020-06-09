# School_District_Analysis
School District Analysis

# Challenge Objectives
- Filter DataFrames using logical operators.
- Replace the incorrect values with NaN.
- Explain how your PyCitySchools analysis changes after you handle the incorrect data.  


##How is the data affected after Thomas High School's 9th Graders grades are replaced with NaN because they are incorrect values?

###✓ How is the district summary affected?
average math score: -.01 
Average Reading Score: unchanged
% Passing Math: -1%
% Passing Reading: -1%
% Overall Passing: -1%

###✓ How is the school summary affected?
Observations from per_school_breakdown: 
- Thomas High School has lowered their overall passing percentage by %25
- The % of kids who passed math and reading went down drastically since the 9th graders at Thomas High Schools' statistics were replaced with NaN.
- % passing math decreased by %27 and % passing reading decreased by %28.
- Thomas High has went from a top performing school to a middle/lower ranked school by overall passing percentage

###✓ How does removing the ninth grade scores affect the following:
- Math and Reading Scores by Grade
- For 9th graders, Thomas High School has no data since all data was replaced with NaN.

###Scores by School Spending:
- Thomas High School's data drastically decreased the overall passing percentage for schools spending between $630-644 per student 
- Thomas High School's data decreased the % passing math for schools spending btwn $630-645 by %6
- Thomas High School's data decreased the % passing reading for schools spending btwn $630-645 by %7

###Scores by School Size
- Thomas High's data decreased the % Passing Math of medium sized schools by %6
- Thomas High's data decreased the % Passing Reading of medium sized schools by %6
- Thomas High's data decreased the % Overall Passing of medium sized schools by %6

###Scores by School Type
- Thomas High School's data decreased the % of overall passing math by %4, % passing reading by %4, and overall passing by %3.

###Example of how the NaN affected the data:  

###Before :
School Type			Average Math Score	Average Reading Score	 % Passing Math	  % Passing Reading	    % Overall Passing		
Charter	              83.5	                   83.9	              94	                  97              	90
District	            77.0	                   81.0	              67	                  81	              54


###After inputing all 9th graders at Thomas High School's math and reading scores as NaN: 

School Type					Average Math Score	Average Reading Score	  % Passing Math	   % Passing Reading	  % Overall Passing
Charter	                  83.5	              83.9	                  90	               93	                87
District	                77.0	              81.0	                  67	                81	              54










#Thomas High's data decreased the % Passing Math in Charter Schools by %4
#Thomas High's data decreased the % Passing Reading in Charter Schools by %4
#Thomas High's data decreased the % Overall Passing by %3
