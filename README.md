# eSymposiumDb

### Use the following commands to restore eSymposium database to the saved image below

1. from project's root cd /backup
2. $ mongoimport --db=eSymposiumDb --collection=UserPosts --file=UserPosts.json
3. $ mongoimport --db=eSymposiumDb --collection=SymposiumUser --file=SymposiumUser.json
4. $ mongoimport --db=eSymposiumDb --collection=UserTweets --file=UserTweets.json

