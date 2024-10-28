### How I scraped the Data:
I used GitHub API's end point https://api.github.com/search/users?q=location:Basel+followers:>10 to get a list of all users that are from Basel and have more than 10 followers, Storing their usernames. Then, I used the endpoint https://api.github.com/user/{user_id} to get all the required details for each user. For repositories, I used the endpoint https://api.github.com/user/{user_id}/repos to get details about each repository present for every user, storing all the data in a csv file using python.


