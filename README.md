# giffygram

<ol>
  <li>What components make up this application?</li>
## main.js
### Responsible for rendering all HTML to DOM

## GiffyGram.js
### Responsible for building a GiffyGram function that returns the HTML. 
### Invoked in main.js

## Post.js
### Responsible for a Post function that returns the HTML for a specific post

## PostList.js
### PostList function is responsible for returning the HTML that will display each post on the feed.
### Can add a post (POST method)
### Invoked in GiffyGram.js

## PostEntry.js
### PostEntry function returns a form for a post

## Login.js
### Login function returns form for user to login. 

## NavBar.js
### NavBar function returns links
#### Home
#### New message form
#### Messages
#### Logout

## Footer.js
### FILTERS
#### Posts since year
#### Filters by user
#### Filters by favorites

## Provider.js
### FETCH CALLS
#### Add messages
#### Add posts
#### Delete posts

## MessageList.js
### MessageList function is responsible for returning the HTML that will display each message.

## MessageForm.js
### MessageForm function returns form for user to send message to another user
#### Recipient 
#### Message
#### save

## PrivateMessages.js
### PrivateMessages function returns HTML for private messages

  <li>What state is being tracked in the application?</li>
<li>What state is persistent? Reverse engineer the data and their relationships and build an ERD.</li>
  <li>What state is transient? Is there any state being tracked, but not permanently in the API?</li>
  <li>What event listeners are used in this application? Which components have event listeners?</li>
<li>What fetch calls are used in this application to modify state? What method (GET, POST, DELETE) is used on each?</li>
<li>What bugs/incomplete features still need to be fixed or implemented?
  </ol>
