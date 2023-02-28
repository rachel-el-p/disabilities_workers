#People with disabilities found work during the pandemic, but there's still a wide job chasm to close
##Data Project Assignment 3 

This is my submission for the Data Studio class' third assignment — to create desktop/laptop and mobile versions of my graphics using Adobe Illustrator

I took data from the Bureau of Labor Statistics, Centers for Disease Control and Prevention, and  Equal Employment Opportunity Commission. Some of it were readily available in CSV format; others I compiled into a Google Sheet. For BLS' labor force participation rate and unemployment rate data, which is taken from the [monthly Employment Situation reports](https://www.bls.gov/bls/news-release/empsit.htm#2023).

I used the average rate of men and women aged 16-64. This is the same metholody as the Kessler Foundation and the University of New Hampshire’s Institute on Disability, which [jointly publishes](https://kesslerfoundation.org/press-release/ntide-january-2023-jobs-report-more-people-disabilities-are-striving-work-will) the BLS data with their quotes. 

After collecting the data, I used pandas to clean them a little further and plotted them using ggplot, before cleaning up the graphics on Adobe Illustrator. I used Datawrapper to create the chloropleth map, and RawGraphs to create the bump chart, and cleaned them up in Illustrator.

These are the sources for my data:

| What I plotted  | Data source |
| ------------- | ------------- |
| Labor Force Participation Rate | [BLS' Employment Situation Report](https://www.bls.gov/bls/news-release/empsit.htm#2023) |
| Unemployment Rate | [BLS' Employment Situation Report](https://www.bls.gov/bls/news-release/empsit.htm#2023) |
| Employment discrimination claims  | [EEOC's Charge Statistics](https://www.eeoc.gov/data/charge-statistics-charges-filed-eeoc-fy-1997-through-fy-2021) |
| Wages of various jobs | [BLS' May 2021 National Industry-Specific Occupational Employment and Wage Estimates](https://www.bls.gov/oes/current/oessrci.htm) |
| Percentage of workers in various occuptaions | [BLS' annual Persons with a Disability: Labor Force Characteristics News Release](https://www.bls.gov/news.release/disabl.htm) |
| Age-adjusted rate of people with disabilities in each state | [CDC's Disability and Health Data System](https://dhds.cdc.gov/LP?CategoryId=DISEST&IndicatorId=STATTYPE&ShowFootnotes=true&View=Map&yearId=YR5&stratCatId1=CAT1&stratId1=BO1&stratCatId2=&stratId2=&responseId=Q6DIS1&dataValueTypeId=AGEADJPREV&MapClassifierId=quantile&MapClassifierCount=5) |

And here are the CSV files: 

*[Labor Force Participation Rate and Unemployment Rate from Jan 2019 to Jan 2023](https://github.com/rachel-el-p/disabilities_workers/blob/main/data/Disability%20-%20Monthly%20change%20LFPR%20and%20Unemployment.csv)
*[Job wages and percentage of disabilities in it](https://github.com/rachel-el-p/disabilities_workers/blob/main/data/Disability%20-%20Jobtypes.csv)
*[EEOC Employment Discrimination Claims](https://github.com/rachel-el-p/disabilities_workers/blob/main/data/Disability%20-%20EEOC.csv)
*[Age-adjusted rate of people with disabilities in each state](https://github.com/rachel-el-p/disabilities_workers/blob/main/data/age_adjusted_by_state.csv)

The data shows that though more adults with disabilities have been able to find work compared to pre-pandemic times, people with disabilities are still half as likely to hold a job. And even if they do, there's a higher possibility they are in lower-wage jobs in the retail and service sectors, and less represented in jobs that pay more, such as those in the education and health, and in managerial positions. 

The story webpage is here: https://rachel-el-p.github.io/disabilities_workers/

## Skills learned: 
I learned how to fix ai2html glitches and make a slightly different one for mobile readers. I also practice my ggplot chart-making skills, and learned how to use RawGraphs. I think my Illustrator design skills improved after doing some exercises last week where we tried to recreate some news outlets' graphics, and I managed to apply some of that in this project. 

## Things I would've liked to do:
I would like to make a hexmap instead of a chloropleth map next, practice using the Census Bureau API (although downloading their CSVs is pretty easy),
and make a scatterplot that plots how much the jobs where people with disabilities are in and visualize in a different way if 
people with disabilities are underrepresented in jobs with higher pay and overrepresented in jobs in lower pay. Hopefully I can come back to this soon!
 
