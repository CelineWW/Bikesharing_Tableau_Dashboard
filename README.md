# Bikesharing Dashboard and Stories 
**:small_blue_diamond:Tableau:small_blue_diamond:**

## Overview
Use the experience of New York Citibike as a reference to discover how do the results apply to a new bike-sharing programe in another city -- Des Monies.

1. Download and import data(New York city Citi bike trip data -201908) into Tableau.
2. Change data type of Tripduration to datetime for further analysis.
3. Create visualizations to make analyses via dragging dimesnsions and measures to `Columns` and `Rows`.
4. To opotimize the visualization, some data were dragged into `Marks`, including `Color`, `Size`, `Label`, etc.
5. Create Dashboard and Story by dragging worksheets to `Dashboard` and `Story` pages, and make appropriate arrangement.


## Result
 
 1. The data type of Tripduration was changed to datatime.
    
   ![201908-citibike-tripdata-updated](https://user-images.githubusercontent.com/105877888/186985834-24140f1f-1fdb-455d-90b9-9f922973f40c.png)
   

 2. [Number of rides](https://public.tableau.com/app/profile/celine7593/viz/Citibike-BikeRepairs/BikeRepairs)
 
   ![Number of Rides](https://user-images.githubusercontent.com/105877888/187010074-13fd371a-903b-4025-bb25-50c68f128cbc.png)

   :point_right: Total number of Citibike rides is over 3 millions. This is big success of bike-sharing program in New York city.
   
   
 3. [Top Starting Locations Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-TopStartingLocations/TopStartingLocations)
 
   ![Top Starting Locations](https://user-images.githubusercontent.com/105877888/187010077-65e0f9d1-e16e-4af3-8085-d763fc24c893.png)

   :point_right: The darker and larger the circle is, the more frequently the sharing bike was utilized in this location. High denstiy area is around Empire State Building. There might be more tourist in this area.
   
   
 4. [[Top Ending Locations Viz]](https://public.tableau.com/app/profile/celine7593/viz/Citibike-TopEndingLocations/TopEndingLocations)
 
   ![Top Ending Locations](https://user-images.githubusercontent.com/105877888/187010082-ee34b91f-2b37-4beb-a597-fa551aff1502.png)
 
   :point_right: Top ending locations distribution is very similar to top starting locations. That indicates riders might return bikes to or closeby the original place they rented. Overall, bikes remain the same area. There is no need to do extra effort to move bikes from place to place by Citibike company.
   
   
 5. [Checkout Times for Users Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-CheckoutTimesforUsers/CheckoutTimesforUsers)
 
  ![Checkout Times for Users](https://user-images.githubusercontent.com/105877888/187010090-cdee7761-9bde-44fb-9f05-8532cb2193de.png)
  
  :point_right: Most of users take their bike trip for less than 1 hour, typically 0 ~ 20 minutes. They might ride not very far.

   
 6. [Checkout Times by Gender Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-CheckoutTimesbyGender/CheckoutTimesbyGender)
 
  ![Checkout Times by Gender](https://user-images.githubusercontent.com/105877888/187010091-b956bc69-7e3a-44c6-9d86-3d800ba17d4b.png)
  
  :point_right: Male riders are notably more than female.
   
 7. [Trips by Weekday for Each Hour Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-TripsbyWeekdayperHour/TripsbyWeekdayperHour)
 
  ![Trips by Weekday per Hour](https://user-images.githubusercontent.com/105877888/187010102-92d6b995-9940-42c8-9e20-554de9b87124.png)

  :point_right: 8:00-9:00am and 5:00-7:00pm are the peak hours of using Citibikes on weekdays. People might use them for commutes.

 8. [Trips by Gender (Weekday per Hour) Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-TripsbyGenderWeekdayperHour/TripsbyGenderWeekdayperHour)
 
  ![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/105877888/187010111-143e73b6-4ed6-4bfd-b518-ded72d60fc7e.png)
  
  :point_right: There is no significant difference on bike riding on weekdays or hours. Whereas males contribute more rides than women. 
  

 9. [User Trips by Gender by Weekday Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-UserTripsbyGendernyWeekday/UserTripsbyGenderbyWeekday)
 
  ![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/105877888/187010124-a0700a23-bdb6-42bd-a014-b8fb96af0140.png)
  
  :point_right: Apparently, the number of constant subscribers is more than temporary customers on bike-sharing.


 10. [Bike Repairs Viz](https://public.tableau.com/app/profile/celine7593/viz/Citibike-BikeRepairs/BikeRepairs)

  ![Bike Repairs](https://user-images.githubusercontent.com/105877888/187010134-8e042627-66ff-4633-9405-55a23b64bb95.png)
  
  :point_right: Bikes were not evenly used. Bikes on left top corner were most frequently used. Bikes on right bottom corner were less used. Thus bikes with bike ID on the left top need more care and repair. 
  
 
 11. [Dashboard](https://public.tableau.com/app/profile/celine7593/viz/Citibike-Dashboard_16614511356840/Citibike_Tripdata_Analysis)
 
  ![Citibike-Dashboard](https://user-images.githubusercontent.com/105877888/187010152-1baeef2b-b1c9-4378-aa99-f5e1d03de5d8.png)

  User trips by gender by weekday, trips by weekday per hour, checkout times by gender are displayed on dashboard.
  
  
 12. [Story](https://public.tableau.com/app/profile/celine7593/viz/Citibike-Story_16615332601610/Citibike-Story) 
 
  ![Story](https://user-images.githubusercontent.com/105877888/187010229-1f7c914f-235b-4f4b-8242-7b98703cc249.png)

  All the information above are included in story.
  
## Summary

- Based on the total number of rides, Citibike is big success in New York City. This is an exciting news. However, This data analysis applies specifically to New York city. Kate's hometown Des Moines might be quite different. we must be cautious that some of the results are applicable to Des Monies bike-sharing program. But some are not. For example, according to the starting and ending locations, there might a large amount of rides were from tourist. This can not be promised in Des Monies. Once the bike-sharing programe started, we can analyze the new data collected from Des Monies to make improvements.
- According to subscriber/customer ratio, and peak hour of bike usage, Citibike usages were mainly for commutes.
- For the bike mantainance
  1. The best time period for bike maitainance is between 12:00-4:00am.
  2. Bike conditions are various. Bikes which used more often needs to be checked and repair more frequently. At the same time, in order to maximum bike's life, switching bike loaction would be an efficient way.
- Two additional visulizations are suggested.
  1. `Trips`(Rows) by `Start Station Name` / `End Station Name`(Columns), bar chart sorted by descending order: To show how many bikes should be provided in each station.
  2. `Trips`(Rows) by `Birth Year`(Columns), mark colors by `Gender`(Columns), line chart filtered by `Usertype` with subscriber: To check the users properties of subscribers. Baesd on this result, we can plan appropriate advertisement to specific age and gender group.
   
