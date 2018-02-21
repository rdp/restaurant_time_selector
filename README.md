# restaurant_time_ui

Appears they are already split, and 

Mon-Thu, Sun 11:30 am - 10 pm

If they enter "sunday 3 AM" minute and day

Assume: they want to be able to pick a particular date, not just day of the week+time.

Assume: if it says 11am - 4 am, then it's "not inclusive" for 4am.

Range: minute x -> y, week day z.

Iterate over each restaurant, all ranges, global boolean that can go true for each restaurant.  Vary divs based on that.