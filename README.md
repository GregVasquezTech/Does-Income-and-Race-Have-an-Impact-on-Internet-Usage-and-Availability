# Income-and-Race-on-Internet-Availability

![TotalHouseholds](https://user-images.githubusercontent.com/34047362/145502327-fcf5af25-913c-4dd1-81fc-f5553c280d30.png)

  This project focuses on internet availability for NYC's citizens. It delves into the income status and race of NYC's households. Also, this project compares combined areas that has high internet connection to areas that has low internet connection and see what is available. I decided to do this project because I live in one of the areas in the Bronx that has low opportunities to access internet. Days where I haven't had internet and had to stay in school longer just to finish my work, I wanted to see if my income status and race has an impact on my neighborhood having good internet connection or not. My hypothesis for this project is that your neighborhood, race, and income status does have an impact on internet connection and internet availability.  
  
  Using data from the https://data.cityofnewyork.us/, categorizing and group data, as well as using matplotlib.pyplot to visualize my work, I was able to see that race on its own doesn't have an impact on internet availability. As you can see in the figure below, the data for each race looks identical to each other.

![race_internet](https://user-images.githubusercontent.com/34047362/145502987-e8369be8-8719-44f3-b2dc-7c332362752f.png)

  Next is income. I decided to categorize income status by low-income, middle-income, high-income. With the data I used as well as this pdf, https://www1.nyc.gov/html/mancb10/downloads/pdf/testimonials/cb10-testimony-on-area-median-income-calculation.pdf, I was able to find the range of each income status, and then place each household to their income-status. As you can see from the figure below, income does have an impact on internet availability. While households with no internet for middle and high income status are similar and very low, low-income status households has a higher percentage. This shows that if you are in a low-income household, there is a higher chance that you will be living in a household with no internet. 
  
![IncomeHouseholds](https://user-images.githubusercontent.com/34047362/145502990-9580adac-ac39-4bc4-b7f4-af6e77a2b30b.png)

  Now that we have seen that income does have an impact on internet availability, lets look deeper into the low-income household and figure out why there is a higher percentage of households with no internet compared to middle-income and high-income households. In this part of the project, I decided to use multiple variables to compare low-income households with internet to low-income households without internet. My variables are, 

  NYC Households with Income Below Poverty Level, NYC Households Receiving Assistance from the Supplemental Nutrition Assistance Program, NYC Residents Without a High School Degree, NYC Households with Children Under 17 Years of Age, NYC Residents Who are Black/African American or of Hispanic Origin, NYC Residents Who Speak Spanish as Their Primary Language, NYC Households with People Who Live Alone, NYC Residents 65 Years Old and Older
  
  With these variables, I was able to get a visualization of low-income households with internet and low-income households without internet. This is shown in the figure below.

![Households_With_Without_Internet](https://user-images.githubusercontent.com/34047362/145502417-4b86e9f7-6224-4140-9e75-0fc03d3e4820.png)

I decided to break it down into a pie chart to see the percentage for each variable in a low-income household with internet. When you compare both of the pie chart, the majority of it is minorities (combine the purple and brown slices). 

![Household With Internet](https://user-images.githubusercontent.com/34047362/145502430-a64c59e4-9926-4317-92f0-7d0585f24571.png)

![Household Without Internet](https://user-images.githubusercontent.com/34047362/145502444-9177aae3-c86d-4b65-880c-a8277bea965a.png)

![High_Connections_NYC](https://user-images.githubusercontent.com/34047362/145502461-3d351e11-d864-4fad-b718-ccf92e4d65c2.png)

![Low_Connections_NYC](https://user-images.githubusercontent.com/34047362/145502486-d1b08be9-9cef-4071-b272-b1b8bbc48ed3.png)

Citations: 
 - https://data.cityofnewyork.us/City-Government/Internet-Master-Plan-Broadband-Adoption-Demographi/6yzk-rwz2/data
 - https://data.cityofnewyork.us/Social-Services/Internet-Access-by-Select-Demographics-in-New-York/9ss3-avyg
 - https://data.cityofnewyork.us/City-Government/Internet-Master-Plan-Adoption-and-Infrastructure-D/fg5j-q5nk/data
 - https://www1.nyc.gov/html/mancb10/downloads/pdf/testimonials/cb10-testimony-on-area-median-income-calculation.pdf
 - https://matplotlib.org/stable/gallery/
