# python-api-challenge
Pulling API's to analyze weather on a global scale and then planning an informed vacation. 

9/17/2021 First Major Commit:
- Struggled on setting up initial API requests. 
- I knew I had to loop through each city, but wasn't sure how it would come together as a dataframe.
- My solution (a simple one) was to create and then fill lists with each request, bind them together into a dictionary and make the dataframe from there.
- Added the try/exception for cities that data could not be found for.
- I believe I made the commit after seeing I could successfully export the data to a .csv

9/18/2021 9:50am Second Commmit:
- Had a little struggle finding the indices for humidity values greater than 100%.
- Otherwise created the indicated scatterplots and then linear regressions by hemisphere.
- Good to have practice with these skills, I think I cleaned up the code and am happy with their look and the analysis.
- Still need to finish analysis on linear regressions.

9/20/2021 Third Commit:
- Had to fix the units from metric to for temperature.
- Started work on VacationPy:
- Created initial heatmap based on humidity. Need to fix zoom level.
- Filtered the weather dataframe based on given parameters to find perfect vacation spot.
- Created a new dataframe with locations, added dummy spaces for hotel information.
- Still need to use Google Places to find hotels in prompted cities then add Pins.

9/21/2021 Last Commit(s):
- Used the API to find nearby hotels following the given parameters, dropped the rows for cities it couldn't find hotels for.
- Tried to change the code so it would reject hotels with a rating of zero and select the next from the request, but didn't figure it out.
- Added the marker pins, struggled a little to get the pre-built info box code to work, but I eventually did.
- Pretty happy with how everything looks at the end:
![image](https://user-images.githubusercontent.com/87144190/134331544-ee2d707c-c100-49c4-beb3-687071cbd13c.png)
