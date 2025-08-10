The program - GEO POINTS - does the following: 
1. Calculates the distance between two geographical points
2. The programs have the following functions:
3. A "header" function that takes no parameters and returns nothing that displays a header.
   The header will print a summary explaining the purpose of the program.
4. A "get location" function that takes no parameters, asks the user for a latitude and longitude,
   and returns a tuple or list with the latitude and longitude. Make sure you tell the user what units to enter their information in!
5. A "calcDistance" function that takes two tuples or lists, each with a latitude and longitude, calculates the distance between those
   two geographical points and returns the distance.6
6. The haversine formula is:
   Given:
         Latitude in decimal degrees: Lat1 and Lat2
         Longitude in decimal degrees: Lon1 and Lon2
         Radius of the Earth R (mean radius = 6,371 km);
   The distance D between points (Lat1, Lon2) and (Lat2, Lon2) can be calculated using:
         A = sin²((Lat2-Lat1)/2) + cos Lat1 ⋅ cos Lat2 ⋅ sin²((Lon2-Lon1)/2)
         C = 2 ⋅ atan2( √A, √(1−A) )
         D = R ⋅ C
7. In the main part of the program (after declaring my functions):
        a.) Call the Header function that displays a header
        b.) The program should allow the user to do multiple calculations. Use a "do another?" loop.
        c.) Inside the loop, the program will do the following: 
                       i.) Call the get-location function to get the first location
                      ii.) Call the get-location again to get the second location
                     iii.) Call the distance function passing in the two locations above as arguments.
                      iv.) Display a nicely formatted message to the user telling them the distance between those two locations
                       v.) Finally, ask the user if they want to do another.

8.  When done, display a goodbye message outside the loop. 
