## How I scraped the Data:
I used GitHub API's end point https://api.github.com/search/users?q=location:Basel+followers:>10 to get a list of all users that are from Basel and have more than 10 followers, Storing their usernames. Then, I used the endpoint https://api.github.com/user/{user_id} to get all the required details for each user. For repositories, I used the endpoint https://api.github.com/user/{user_id}/repos to get details about each repository present for every user, storing all the data in a csv file using python. I used Excel for analysis and answering of various questions asked

## Most Interesting and Surprising Fact
##### Focused Interests Among Basel's Active Developers: 
Among Basel developers with more than 10 followers, there's a trend of specialization. Many of these developers work on projects tied to certain languages and industries, particularly Python and JavaScript for data science and web applications. This trend likely reflects local demand in fields such as finance, pharmaceuticals, and data analytics, aligning with Basel's prominent industry sectors.
##### Quality over Quantity in Project Choices: 
A significant number of Basel developers with higher follower counts tend to focus on a few key repositories rather than numerous projects. This suggests that the community values depth and quality in projects, favoring repositories that offer extensive documentation, well-structured code, and consistent updates.
##### Underutilization of Collaborative Features:
Despite high engagement levels, many popular repositories lack collaborative tools like wiki pages or project boards. This absence could indicate that developers in Basel prioritize solo project work or haven't fully tapped into features that facilitate community contributions.

## Actionable Recommendation for Basel Developers
##### Engage with Specialized Communities to Boost Visibility: 
Basel developers can further expand their visibility by connecting with relevant open-source communities in their industries. Actively contributing to projects in high-demand sectors like data analytics or finance could help them gain both followers and professional opportunities.
##### Focus on Project Depth and Maintenance: 
Since high follower counts often correlate with a small number of high-quality repositories, Basel developers should continue investing in well-documented, regularly maintained projects. Enhancing usability and providing clear documentation can attract more stars, watchers, and potential collaborators.
##### Enable Collaborative Tools to Encourage Contributions: 
Basel-based developers could leverage GitHub’s project boards and wikis to encourage contributions from others. Opening up their repositories for collaboration can create a more dynamic and interactive GitHub profile, which could help developers build a network and support long-term project growth.

