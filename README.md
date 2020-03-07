# Spiderbook v2
Website made for the Arachnid network. All users are anonymous, but their IP's will be put in the database for spammers and other rule violators.

----
## Q&A: Not questions you asked, but questions you deserve
### How will you code the API?
> api.py will contain functions that take in a Flask request and return the appropriate data in dictionary format. It will use dbint.py to interact with the database.

### How will you make the frontend?
> I plan on using Grid and Flexbox for the layouts, which will be relatively simple. I may, at some point, add some prettier decorations, but at first it will be a flat, simplistic design.

### How will you code the backend?
> The backend is being made with Python, with Flask taking care of requests. The Database is going to be made with PostgreSQL with a file named 'setup.psql' containing all the necessary code to set it up on your machine.

### How long do you think this will take?
> It should be done by May of 2020.

### Why do you just not work every few weeks?
> Either because of school or family.

----    
## TODO:
- **API**:
    - (done) raw database interactions
    - (done) add post
    - (done) add reply
    - (done) add reply to post reply list
    - (done) delete post or reply
    - (done) get post or reply
    - (done) get n posts or replies
    - (done) get n posts or replies based on parent
    - (done) edit post or reply body
    - (done) escape SQL data to prevent SQLi attacks
    - (done) superuser signup
    - (done) accept superuser application
    - (done) superuser request verification (name/password on each superuser action)
    - (done) escape remaining SQL data
    - (done) [mod] ban ip (hourly limit)
    - (done) fix delete function to delete all replies and remove self from parent's reply list
    - (done) [mod] unban ip
    - (done) [mod] get all banned ips
    - (done) [admin] get all admins and moderators
    - (done) [admin] remove moderator

- **View Functions**:
    - (in progress) add post
    - add reply
    - delete post
    - delete reply
    - get post and all of it's replies
    - get n posts based on category
    - edit post
    - edit reply
    - superuser signup
    - [mod] ban ip address for x hours
    - [mod] unban ip address
    - [mod] get all banned ip addresses
    - [admin] accept superuser
    - [admin] get all admins and moderators
    - [admin] remove moderator

- **Frontend**:
    - home page
    - single post page
    - proper comment parsing (comment a bit to the right of original post)
    - [mod] moderation dashboard tab
    - [admin] administration dashboard tab

