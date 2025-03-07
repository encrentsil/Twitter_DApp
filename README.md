# Twitter_DApp
This is a simple Twitter dApp developed to learn some Blockchain and Solidity concepts

FUNCTIONS

createTweet(): This function is used to create a tweet. It accepts imput from the user in order to create the tweet

viewTweet(): This function helps us to view a particular tweet by accepting the author of the tweet and the index of the tweet as arguements

getAllTweets(): This function returns an array of all the tweets of a user by passing the address of the user as an arguement

changeTweetLength(): This function is used to change the the number of characters a tweet can contain Only the owner can change the length

likeTweet(): This function is used to like the tweet of a particular user by passing the address of the author and the tweet Id as arguement

unlikeTweet(): This function is used to unlike the tweet of a particular user by passing the address of the author and the tweet Id as arguement

numberOfTweets(): Returns the number of tweets a user has made

followUser():  Users can follow eachother

unfollowUser(address _user): Users can unfollow eachother

getFollowers(): View a user's followers 

getFollowing(): View who a user is following