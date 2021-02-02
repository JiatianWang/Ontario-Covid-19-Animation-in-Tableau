# Ontario-Covid-19-Animation-in-Tableau
I conducted an animation of Ontario Covid19 daily confirmed cases from 2020 Jan to 2021 Jan with Tableau.

I downloaded the data from the data Ontario website. This data set complies daily snapshots of publicly reported confirmed cases in Ontario. Data mainly includes reporting date, test outcomes, the geolocation of current patients, age group, patient gender and so on. 
Before reading the data into the tableau, I loaded the data set into the Python to check if the dataset is proper organized. After that I derived the desire variable based on the test outcome.
With the prepared the data, I loaded into tableau to create this animation.

As we can see from the left side, there is the Ontario map with city names. Different colors and sizes of the circles represent the covid-19 status in each city. The larger the circles, the higher number of the confirmed cases.  At the upper right side, it’s the confirmed cases overtime. At bottom, it is the accumulated cases in each city. It turns out that Toronto, Mississauga, Newmarket are the severe infected area./ 

If we look at the beginning of the epidemic, there was a small increase in the number of people diagnosed. In June, July, August, September the outbreak seems to be under control, with lower number of cases daily. However, by October, the confirmed cases surprisingly increased, and every day hit the new record.

![covid19](https://user-images.githubusercontent.com/32876600/105769538-f430bf80-5f2b-11eb-98f7-0cc09c50c1bc.JPG)

Video:
https://user-images.githubusercontent.com/32876600/105879898-bafe5b00-5fd0-11eb-94bd-2e05ce10a876.mp4

There are 3 outcomes of resolved, not-resolved, fatal. The annimation and screenshot are down below,which are the outcomes overtime. The first graph is the comfirmed cases.

![4 outcomes](https://user-images.githubusercontent.com/32876600/106620070-35822a00-653f-11eb-9fdd-611383bf6fda.JPG)

https://user-images.githubusercontent.com/32876600/106620393-85f98780-653f-11eb-8874-c4aaf368047b.mp4

At the beginning of the epidemic, the fatality rate was relatively high from the end of March to the beginning of May, and the epidemic was well controlled from June to September, with low incidence and fatality rate. 

But since October, the number of diagnoses has increased rapidly, reaching a peak in mid-January, but the cure rate is very high. The number of not-resolved people is very high. I suppose there are two possible reasons behind. The first cause is that the virus has mutated and no cure has been found yet, the second cause is that hospitals have reached their capacity to receive patients.

Outcomes for Male and Female in different age groups

![agegroup](https://user-images.githubusercontent.com/32876600/106620595-b6d9bc80-653f-11eb-8dc5-272d8eb6e464.JPG)

Overall, there were more women than men in all three outcomes.

For both men and women, the highest number of people in the three categories of confirmed, cured and uncured are in their 20s. 

The number of people diagnosed and cured declines after the age of 60, but more women than men. 

The number of deaths after 60 accounted for 95.6% of total deaths toll. 

The fatality rate for both genders was very low under 50. The death rate for women is lower than for men. After the age of 80, female death rates rise, and male death rates decline.






