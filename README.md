# Module 4 Challenge: PyCitySchools Test Scores



## Overview of the school district analysis

We were tasked with preparing a school district's standardized test data for analysis, reporting, and presentation to provide insight about performance trends and patterns.  
  
These insight will, in turn, be used to inform discussion and strategic decisions at the school and district level. Through the preparation and analysis of student funding and standardized test scores, we were to aggregate the data and showcase trends in school performance to assist the school board and superintendent in making decisions regarding school budgets and priorities.  
  
After conducting this analysis a first time, the school board notified us that our data file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appeared to have been altered. 

We were asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact before repeating our analysis and reporting on how these changes affected the overall analysis.

## Results

- How is the district summary affected?
	
	As we were tasked to change test scores for one grade in one school, the effects on the district summary were fairly minimal since this subset of the population turned out to not be very large. The district summary initially went from this:
	
	To this:
	
	There seem to be a little bit of variation in the percentages but most of the rest of the data including total schools, total students and total budget remain unchanged.
	
- How is the school summary affected?
	
	As in the district summary, most data remains unchanged in the school summary except for the various passing percentages for Thomas High School.
	
	The school summary initially went from this:
	
	To this:
	
	
	We notice a significant improvement in the passing percentages for Thomas High School as all the 9th graders scores were essentially dropped and those students were not counted to calculate passing percentages.
	
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- How does replacing the ninth-grade scores affect the following:


	- Math and reading scores by grade
		
		The math and reading scores by grade both showed NaN for 9th grade at Thomas High School. This means they went from this:
		
		
		Math scores by grade
		
		
		Reading scores by grade
		
		To this:
		
		
		Math scores by grade
		
		
		Reading scores by grade		
		
		
	- Scores by school spending
		
		
	- Scores by school size
	
	
	
	- Scores by school type
	
		

## Summary
