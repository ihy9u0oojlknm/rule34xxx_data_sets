The rand\_user\_data100k dataset is a collection of user data from approximately 100,000 users. The data stored was gathered from the **https://rule34.xxx/index.php?page=account&s=profile&uname=USER\_NAME\_HERE** page for each user.

This dataset was scraped from the site from approximately June 25th to June 26th of 2026.

  

## For each user, the following datapoints are stored:

- user-id
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

  

## JSON version

The JSON version of the dataset uses strings of the user-ids as the keys. Connected to each user-id key is a JSON dictionary with fields for each datapoint except for user id for that user.

The keys for each user datapoint are as follows:

- user\_name
- join\_date
- posts
- deleted\_posts
- favorites
- comments
- tag\_edits
- note\_edits
- forum\_posts

  

## PKL version

This version is the pickle for a python Pandas DataFrame Object. Use pandas.read\_pickle() to load it.

The DataFrame it represents stores each users data in one row with each column corresponding to each datafeild.

The columns for the DataFrame are as follows:

- user\_id
- username
- join\_date
- level
- posts
- deleted\_posts
- favorites
- comments
- tag\_edits
- note\_edits
- forum\_posts
