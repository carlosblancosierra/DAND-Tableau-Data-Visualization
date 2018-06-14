Data Storytelling Project of the Data Analyst Nanodegree by Udacity

Tableau Story: https://public.tableau.com/profile/carlos7878#!/vizhome/Project_Delayed_Flight_Info_v4/Story2

I Created a data visualization that tells a story or highlights trends and patterns in a data set. 
I used Tableau to create the visualization. The work is a reflection of the theory and practice of data visualization, 
such as visual encodings, design principles, and effective communication.

The data set contains information on United State flight delays and performance from RITA.

I made 4 versions of the project, because it was a requirement that I ask for feedback and implement the corrections
mentioned. I created an html file with the walktrought for the project with summarys, design and cleaning choices and 
the feedback I received 


Summary:

If US airports are sorted by the numbers of flights arrived in, the top 50 airports have 79.38% of all arrived flights. 
They each have an average of 1.903.014 arrived flights from 2007 to 2017. This analysis will on take into consideration 
those 50 airports, to determine the causes and statistics of the delayed flights of these airports.

Around 20.9% of the arrived flights landed with more than 15 minutes of delay, with an average of 53.62 minutes of delay.
This average of delayed flights is solid, since it is very close to the median of and the interquartile range is 1.7%. Also,
the delay time average is close to its mean of 52.61, with an interquartile range of 4.03 minutes.

Newark Liberty Airport has the highest average of delayed with 30.19%, however La Guardia and San Francisco had 28% and 27.6% 
respectively.

Plotting Arrived flights vs either Average Delayed minutes and % of Delayed Flights we can see that there is no positive 
relationship between the number of flights and the delayed minutes, which are stable across the top 50 airports. On the 
other hand, the % of delayed flights have a slightly positive relationship with the number of flights and the % of delayed 
flights

If we Analyze the carriers, we can see that there are some high flight carriers with low % of delayed and delayed minutes 
average, and some small airports with high delays time and percentage. For that reason, the amount of flights does not seem 
to be a big influence on delayed statistics

When taking into consideration the delay type, we can see that late aircraft, National Airspace System (NAS) and carrier delay 
share most of the delay minutes, and the distribution is similar trough all airports, however nas delay have a higher 
percentage on top airports.

There is a clear increment of the Average of Delayed Flights on June, July and December, also, the average delayed minutes 
increment over those same months but with less variation.

We might think that more flights take place between the months with higher delays, however march is the month with higher 
amount of flights, and June, July and December very close to the mean.

Files:
- Project Explanation: Project.html
- Assesing and Cleaning the data: data_wrangling.ipynb.
- Original Dataset: 222954318_122017_4856_airline_delay_causes.csv.zip
- Modified Dataset: us_delayed_flight_info_2007_to_2017.csv.zip



