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

Create the Checkout Times for Users Viz

<img width="1082" alt="CheckoutUser" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/bf75c187-2609-4f0c-8e83-ea185996ed09">

Create the Checkout Times by Gender Viz

<img width="1087" alt="CheckoutGender" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/6a4699e0-9882-4cc8-9ef6-fe669c795630">

Create the Trips by Weekday for Each Hour Viz

<img width="513" alt="TripsEachHr" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/393e1fe6-70ce-4165-ad4c-8e87bb9b530a">

Create the Trips by Gender (Weekday per Hour) Viz

<img width="1085" alt="GenderTripsHr" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/7cde0a77-8b2d-4d15-95cd-0c4decf89b01">

Create the User Trips by Gender by Weekday Viz

<img width="356" alt="WeekdayGender" src="https://github.com/Jall3n/Module15_CitiBike/assets/119149740/94f77b19-e813-4dff-b9cc-1c397d9540a0">


## Summary
