# Movie-Recommendation-System
Tech Stack : Python, ML (NumPy, Pandas, Seaborn, Matplotlib)<br>
***

I have created a Movie Recommendation System using the popular Dataset named "MovieLens 100k". <br>
Performed exploratory Data Analysis on the Dataset to find interesting patterns and trends and check assumptions. <br>




<img width="443" alt="ratings_histogram" src="https://user-images.githubusercontent.com/85777009/178116850-9788d88e-2d35-4c80-b85f-f39e4073aefb.png">
I plotted histogram of movie ratings present in the Dataset and found that the the distribution was like a normal distribution where the mean is around 3.0 <br>
So, most of the users have rated any movie as 3. Also, you all may be aware that Most of the real life dataset belongs to normal distribution and "MovieLens 100k" also follows the same thing.
This was one conclusion that i got. <br> <br>

Next, I made a jointplot to see how number of ratings done by users and average rating varies. <br> <br>
<img width="454" alt="jointplot" src="https://user-images.githubusercontent.com/85777009/178117383-100feea9-0e8f-4d46-b931-605feb50540a.png">


You can observe that this jointplot follows a Linear trend i.e. as the average rating of a particular movie increases,the number of ratings given by users for that particular movie also increases. <br>
<br>
After that I implemented code to find Correlation of each movie with other movies present in the Dataset using pandas’ correlation
function. This will help to recommend similar movies to the user by showing names of movies from Dataset which has highest correlation with the movie user is searching for.<br> <br>

At last,created a predict movies function that takes any movie name as input and gives the recommendations as output. <br>

<img width="1149" alt="predictions" src="https://user-images.githubusercontent.com/85777009/178138675-4072fea8-c4eb-4743-838d-ba5915a95405.png">

