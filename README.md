# CA06 – kNN Based Recommender System 
## Data Source and Contents 

Have you ever come across a film and wanted to know what other films it resembles based on the genre? We can actually create a recommender system to give us recommended movies based on genre information from any given film.  

The sample dataset we will be using is obtained from the UCI Machine Learning Repository and is found at the following url in csv format: 

"https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv”, a Github location. Use the GitHub link in 
your Python code to “read” the data into a Data-frame. 

        cardiodis = pd.read_csv('https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv')  

----------------------------------------------------------------------------------------- 
## Computer Assignment Road Map

**Part 1:** Load the data and perform the necessary EDA 

    1. Read in data and import necessary packages 
    2. EDA 
    3. Drop the 'Label' column as we will not be using it   

**Part 2:** Build the recommender system 

    1. Create new variables with x representing the features and y representing the movie name 
    2. Training is not necessary for kNN 
    3. Implement the model 
    4. Define a variable (the_post) for the film we are recommending movies for 
    5. Return the distances and indices
    6. Return movie titles based on genre information 

-----------------------------------------------------------------------------------------
## Additional Comments 
Google Colab File has been linked to this repository.  However, should you make any adjustments, create a copy of your own to edit. 
