
# Loan Exploration by Aaron Johnson

[Visualization 1 (pre-feedback)](https://public.tableau.com/shared/6BQQ62XJB?:display_count=yes) 

[Visualization 2 (post-feedback)](https://public.tableau.com/shared/TDSPDF4QR?:display_count=yes)

## Summary

In this visualization I will show how loan amounts have changed for a particular data set over a period of 10 years. The data set contains information on 113,937 loans, and all are within the United States. The variables we will be looking at are the sum of original loan amounts, the average of original loan amounts, as well as the categories or types of loans. 

## Design

I first wanted to show the different types of loans that are represented and I thought it would be interesting to see the sum total amount of each one. For this I created a bar chart with the *Listing Category* in the `Columns` field and the sum of the *Loan Original Amount* in the `Rows` field. 

Next I thought it would be nice to show loan amounts geographically by state over time. I decided to show this by using a shaded graph with the shade representing the sum of all loan amounts for each state. Then I added a filter for *Listing Category* so that we could see the total loan amounts for each state from year to year.

With the map information I could see that loans were definitely changing from year to year, and I thought it would be interesting to see if loan amounts were on-average increasing over time. So I decided since we were finding an average that we could use a line graph to chart the average loan amount from year to year. 

In order to bring all this information together I created a dashboard with the map on top and the bar chart and line graph on the bottom. Having the map on the top caused the map to zoom out in order to fill the space. After getting feedback about how it would be better if the map zoomed in on only the United States, I moved the map below to a smaller container. This centers everything nicely on the United States and looks much cleaner. 

I removed the titles for each container in the dashboard since they were a bit distracting, and weren’t displaying any relevant information. I also made sure my filters were connected across the containers so that everything updated automatically depending what years and loan categories where selected. I decided to disconnect the year filer from the line graph showing average loan amounts over time because if only one year is selected, then there would only be one data point. This seemed to be counter to the purpose of the line graph in the first place since it was there to show changes over time. So after making the update, the line graph only responds to changes in listing category.


## Feedback

In order to get feedback I approached someone I know who works with data on a day to day basis. When I presented the visualization to them for feedback the first thing I noticed was that they seemed unsure of where they should start because I only had a dashboard that combined the three sheets. For example, at first they couldn’t tell what the dark colors on the map represented. I showed them the filter bar to the right of the visualization and explained what each color represented. I then asked if maybe I should change from just a monochrome shade of blue, to showing a blend of complementary colors. They said that no, they actually preferred the monochrome shade of just one color because they can more easily identify based on value. 

I guess my initial thinking was that since I was only showing three sheets that it would be okay to just present everything as a dashboard. This person was able to finally understand what was going on, but only after quite a bit of digging around. For some reason my map got a bit zoomed out when I created the dashboard, and my reviewer said that it would be better if we could zoom in. 

Taking all this into consideration, I decided it would be best to present the visualization one piece at a time through the use of a story. That way there would be less information up front to confuse the viewer and allow them to expand out as the explored each sheet. Then I would end the story with the dashboard, so they could see the whole picture and how everything is related.

## Resources

N/A
