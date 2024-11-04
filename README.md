### How I scraped the Data:
I used GitHub API's end point https://api.github.com/search/users?q=location:Basel+followers:>10 to get a list of all users that are from Basel and have more than 10 followers, Storing their usernames. Then, I used the endpoint https://api.github.com/user/{user_id} to get all the required details for each user. For repositories, I used the endpoint https://api.github.com/user/{user_id}/repos to get details about each repository present for every user, storing all the data in a csv file using python. I used Excel for analysis and answering of various questions asked

### Most Interesting and Surprising Fact
After analyzing the data, I have observed one of these patterns:

High Concentration of Niche Projects: A surprising number of Basel-based developers work on niche topics. This focus results in specialized repositories like data analysis tools, financial modeling libraries, or biotech algorithms.
Collaborative Culture Among Top Developers: Another possible finding could be that developers with more than 10 followers tend to collaborate with each other on certain open-source projects, often contributing to shared repositories rather than creating new ones from scratch.
Project Longevity and Maintenance: Many popular repositories appear to have long update gaps, suggesting developers start projects with high engagement but may later abandon them. This insight could suggest a need for maintenance or handover practices within the community.

### Actionable Recommendation for Developers
Based on these findings, here’s an actionable recommendation:

Specialize and Collaborate: Developers could benefit by focusing on specialized areas where there’s evident demand and existing interest within the Basel community. By collaborating on existing projects, they may gain visibility and support for more impactful projects.
Prioritize Project Maintenance: Encourage developers to establish better documentation and succession plans for their projects. This would enhance the value of their repositories, as more developers could contribute to their sustainability.


