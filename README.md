# Module 4 Challenge: PyCitySchools Test Scores



## Overview of the school district analysis

We were tasked with preparing a school district's standardized test data for analysis, reporting, and presentation to provide insight about performance trends and patterns.  
  
These insight will, in turn, be used to inform discussion and strategic decisions at the school and district level. Through the preparation and analysis of student funding and standardized test scores, we were to aggregate the data and showcase trends in school performance to assist the school board and superintendent in making decisions regarding school budgets and priorities.  
  
After conducting this analysis a first time, the school board notified us that our data file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appeared to have been altered. 

We were asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact before repeating our analysis and reporting on how these changes affected the overall analysis.

## Results

- How is the district summary affected?
	
	As we were tasked to change test scores for one grade in one school, the effects on the district summary were fairly minimal since this subset of the population turned out to not be very large. The district summary initially went from this:
	
	![original_district_summary](https://user-images.githubusercontent.com/76575162/119297069-d6e0d900-bc1f-11eb-9359-26940cee2e10.png)

	To this:
	
	![corrected_district_summary](https://user-images.githubusercontent.com/76575162/119297079-da746000-bc1f-11eb-8b77-7d6cffd68280.png)


	There seems to be a little bit of variation in the percentages but most of the rest of the data including total schools, total students and total budget remain unchanged.
	
- How is the school summary affected?
	
	As in the district summary, most data remains unchanged in the school summary except for the various passing percentages for Thomas High School.
	
	The school summary initially went from this:
	
	![original_school_summary](https://user-images.githubusercontent.com/76575162/119297110-ecee9980-bc1f-11eb-91f2-3b6f63c1f7f5.png)
	

	To this:
	
	![corrected_school_summary](https://user-images.githubusercontent.com/76575162/119297107-e95b1280-bc1f-11eb-8b40-a94d78f5529c.png)

	
	We notice a significant improvement in the passing percentages for Thomas High School as all the 9th graders scores were essentially dropped and those students were not counted to calculate passing percentages.
	
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

	As we removed the 9th grades scores form Thomas High School and the passing percentages went up significantly, it caused Thomas High School to be among the top 5 best performing schools, making it to second best overall as can be seen here:
	
	![corrected_top5](https://user-images.githubusercontent.com/76575162/119298941-a438df80-bc23-11eb-82f3-d2bcc6d58646.png)


- How does replacing the ninth-grade scores affect the following:


	- Math and reading scores by grade
		
	The math and reading scores by grade both showed NaN for 9th grade at Thomas High School. This means they went from this:
	
	![original_math_bygrade](https://user-images.githubusercontent.com/76575162/119297128-f7a92e80-bc1f-11eb-9bba-e63f9bf72e9e.png)

		
	Math scores by grade
		
	![original_reading_bygrade](https://user-images.githubusercontent.com/76575162/119297132-fb3cb580-bc1f-11eb-8478-949665f6fabb.png)

		
	Reading scores by grade
		
	To this:
		
	![corrected_math_bygrade](https://user-images.githubusercontent.com/76575162/119297153-042d8700-bc20-11eb-8ba7-f5f0ba545b1d.png)

	Math scores by grade
		
	![corrected_reading_bygrade](https://user-images.githubusercontent.com/76575162/119297161-07c10e00-bc20-11eb-9233-0a4255ef130e.png)

	Reading scores by grade		
		
		Other than the 9th graders scores from THS becoming NaN, no changes here.
		
		
	- Scores by school spending


	![original_spending_summary](https://user-images.githubusercontent.com/76575162/119297182-127ba300-bc20-11eb-9476-4992990d968a.png)
	
		Original
		
	![corrected_spending_summary](https://user-images.githubusercontent.com/76575162/119297248-350dbc00-bc20-11eb-9940-b7b6103a91d2.png)
	
		Corrected
		
		
	
	


	
		
	- Scores by school size
	
	
		![original_size_summary](https://user-images.githubusercontent.com/76575162/119297302-4b1b7c80-bc20-11eb-84cb-ed9c0b83caf6.png)
	
		![corrected_size_summary](https://user-images.githubusercontent.com/76575162/119297307-4d7dd680-bc20-11eb-8e18-890184dd676f.png)




	
	- Scores by school type


		![original_type_summary](https://user-images.githubusercontent.com/76575162/119297254-3b039d00-bc20-11eb-9e26-9bb23e4cdc1f.png)
		
		original
	
		![corrected_type_summary](https://user-images.githubusercontent.com/76575162/119297274-3f2fba80-bc20-11eb-8b9d-1e72c560b803.png)
		
		corrected
		

## Summary

Thomas High School ended up showing higher average test scores.  

Thomas High School ended up becoming number two top performing school.

Thomas High School had a smaller amount of students to count.

Thomas High School had a higher overall passing rate.
