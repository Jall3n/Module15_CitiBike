# Module15_CitiBike
## Purpose

The investors need some more convincing that a bike-sharing program is a good business proposal. So they want to see a bike trip analysis featuring the following:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week

## Results

### Deliverable 1: Change Trip Duration to a Datetime Format:

      citibike_df['tripduration'] = pd.to_datetime(citibike_df['tripduration'], unit='m')
      
### Deliverable 2: Create Visualizations for the Trip Analysis:

Create the Checkout Times for Users Viz: The majority of the checkouts are within 1 hour and there is around 146,000 records of 5 min trip durations. 

<img width="1082" alt="CheckoutUser" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/bf75c187-2609-4f0c-8e83-ea185996ed09">

Create the Checkout Times by Gender Viz: We still see the majority of checkouts are within 1 hour, but it is a larger number of male riders that are using the bikes.

<img width="1087" alt="CheckoutGender" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/6a4699e0-9882-4cc8-9ef6-fe669c795630">

Create the Trips by Weekday for Each Hour Viz

<img width="513" alt="TripsEachHr" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/393e1fe6-70ce-4165-ad4c-8e87bb9b530a">

Create the Trips by Gender (Weekday per Hour) Viz

<img width="1085" alt="GenderTripsHr" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/7cde0a77-8b2d-4d15-95cd-0c4decf89b01">

Create the User Trips by Gender by Weekday Viz

<img width="356" alt="WeekdayGender" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/94f77b19-e813-4dff-b9cc-1c397d9540a0">

August Peak Hours: The three busiest times are 8 AM, 5 PM, and 6 PM which falls in line with the typical work commute

![Screenshot 2023-05-24 at 6 29 18 PM](https://github.com/Jall3n/Module15_CitiBike/assets/119149740/477dc076-6137-4588-b986-171c0e4006cc)

Starting and Ending Location Map: The largest Starting and Ending Longitude and Latitude are the same at Lat: 40.7519 and Long: -73.9777

Starting Map
![Screenshot 2023-05-24 at 6 28 42 PM](https://github.com/Jall3n/Module15_CitiBike/assets/119149740/1173c1fd-7db4-44c1-866c-4be753eeb3d8)

Ending Map
![Screenshot 2023-05-24 at 6 28 59 PM](https://github.com/Jall3n/Module15_CitiBike/assets/119149740/d11fc9d4-3ea9-4785-aa0c-5b27d9483161)





## Summary
