# cijs44final
## AUTH
1. Register
2. Login
## MAIN
3. Swipe
4. Chat
## RIGHT
5. Profile
## LEFT
6. List of Matches
7. List of Who likes me
## SETTING
8. My profile settings



## DB:

- users
  + name
  + age
  + email
  + phone
  + password
  + gender (male, female, other)
  + interested gender (array,)
  + images (array, max 6)
  + punchLine (max 500 chars)
  + createdAt
  + updatedAt
  + lastActive
  + likesReceived (array)
      [{
       + created at
       + user (email)},]
  + likedGiven (array)
      [{
       + created at
       + user (email)},]
  + matches (array)
      [{
       + created at
       + user (email)},]

- conversations
  + createdAt
  + messages (array)
       [{
       + createdAt
       + owner
       + content
       + users (2)},]




