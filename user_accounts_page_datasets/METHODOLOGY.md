The rand\_user\_data100k dataset is a collection of user data from approximately 100,000 users. The data stored was gathered from the **https://rule34.xxx/index.php?page=account&s=profile&uname=USER\_NAME\_HERE** page for each user.

This dataset was scraped from the site from approximately June 25th to June 26th of 2026.

  

## For each user the following datapoints are stored:

- user id
- username
- join date
- level (Members, Banned, Retired, Supporter)
- number of posts
- number of deleted posts
- number of favorites
- number of comments
- number of tag edits
- number of note edits
- number of forum posts

The "Favorite Tags" and "Record" fields from the account profile page were dropped because they were redundant. At this time, it seems that the "Favorite Tags" feature was never implemented, or at least all users in the set had its value equal to "None". Similarly, the "Record" field for all users was "(add)".

  

## json version structure

  

## pkl verion structure
