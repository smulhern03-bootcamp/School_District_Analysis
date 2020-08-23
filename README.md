# School_District_Analysis
## Purpose
Evidence has come to light of academic dishonest at Thomas High School.  Specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards.  The ninth graders' data for reading and math are to be replaced with NaNs while other grades are to be left intact.  After replacing the data, the previously conducted school district analysis is to be repeated to measure the impact of the dishonesty.

## District Summary Impact
The removal of the 9th graders from Thomas High School had a slight impact on the District's scores.  Unsurprisingly, all the scores were lowered - some more than others.

This is the new analysis
![Image of new analysis](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Distict%20Summary%20New.PNG)
This is the old analysis
![Image of old analysis](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/District%20Summary%20Old.PNG)

However, the impact is negated when rounding occurs.  This is not surprising given that Thomas High School only had 461 9th graders, so the impact of their removal out of a district with 39,170 students would not be significant on a district-wide level.

## School Summary Impact
The removal of the 9th graders from Thomas had a severe impact on Thomas High School's scores.  This is understandable given the school had an entire grade level's worth of data removed.

This is the old school analysis
![Image of old school analysis](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Thomas%20High%20School%20old.PNG)

This is the new school analysis
![Image of new school analysis](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Thomas%20High%20School%20new.PNG)

After replacing the overall data with the data taken from only 10th - 12th graders.  Thomas High School is ranked #2 in the district.
![Image of top 5 ranksings](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Top%205.PNG)How does replacing the ninth-grade scores affect the following:

## Math and reading scores by grade
The follwing is the analysis of the impact of removing 9th graders from math and reading.

This is the old math analysis

![Image of math old](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/math%20scores%20by%20grade_old.PNG)

This is the new math analysis

![Image of math new](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/math%20scores%20by%20grade_new.PNG)

This is the old reading analysis

![Image of reading scores old](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/reading%20scores%20by%20grade_old.PNG)

This is the new reading analysis

![Image of reading scores new](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/reading%20scores%20by%20grade_.new.PNG)

The impact was restricted to the pure absence of 9th grader data (NaN) as other grades did not have data removed, these were not impacted.

## Scores by school spending
Similiar to the other analysis, the impact of the removal of Thomas 9th graders is marginal compared to their scores being left.

This is the old analysis
![Image of spending old](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/spending_old.PNG)

Thomas High School, which falls in the $630-$644 bin, saw marginal decreases across the board.  However, this decrease is negated if the scores are rounded.

This is the new analysis
![Image of spending new](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Spending_new.PNG)

## Scores by school size
Thomas High School has 1635 students and falls within the Medium bin for school size.

This is the old analysis
![Image of size old](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Size_old.PNG)

Average Reading Score was the exception and had a marginal increase with the removal of the 9th graders.  All other scores were decreased.

This is the new analysis
![Image of size new](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/Size_new.PNG)

## Scores by school type
Thomas High School is a Charter school.

This is the old analysis
![Image of type old](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/type_old.PNG)

Similiar to the "Scores by school size", Average Reading Score being the exception, all other scores were decreased with the removal of the 9th graders.

This is the new analysis
![Image of type new](https://github.com/smulhern03-bootcamp/School_District_Analysis/blob/master/type_new.PNG)

## Summary of Changes
Overall, the impact of removing Thomas High School's 9th graders had marginal impact on any category other than School rankings.  The District summary, scores (math and reading; school spending, school size and school type) were all marginally impacted - by hundredths of percents.  These impacts are negated if the data is rounded.  The most impact was on Thomas High Schools ranking compared to other schools.  The removal of an entire grade dropped all scores significantly.
