# Scribo
###### I Write
<a href="http://imgur.com/iCLn9Av"><img src="http://i.imgur.com/iCLn9Av.png" title="source: imgur.com" /></a>
### Screenshot

### Links

### About
Scribo is a judgement free platform that connects aspiring writers with other writers and bibliophiles that want to read a story. Writers can use this app to get advice from other writers on the message board, get random writing prompts, post their stories and sell their stories in the BookStore. Anyone can read a story or create a story, but only logged in users can create, update and delete posts tied to their account.

### Wireframes
<a href="http://imgur.com/j2MBNo3"><img src="http://i.imgur.com/j2MBNo3.png" title="source: imgur.com" /></a>
Home: Carousel slideshow that displays highlighted stories and writers

<a href="http://imgur.com/LeLGCsN"><img src="http://i.imgur.com/LeLGCsN.png" title="source: imgur.com" /></a>
Stories: Search the will render results according to genre, name, post date, or author.

<a href="http://imgur.com/8twHiYv"><img src="http://i.imgur.com/8twHiYv.png" title="source: imgur.com" /></a>
FAQ: Frequently asked questions, answered by the admin

<a href="http://imgur.com/lVUZCxe"><img src="http://i.imgur.com/lVUZCxe.png" title="source: imgur.com" /></a>
Login: User login page; user has ability to log into existing account or sign up to create an account

<a href="http://imgur.com/PyoJNH9"><img src="http://i.imgur.com/PyoJNH9.png" title="source: imgur.com" /></a>
Contact: Form that sends user input to the Scribo admin email upon form submission 

<a href="http://imgur.com/uz5zCTa"><img src="http://i.imgur.com/uz5zCTa.png" title="source: imgur.com" /></a>
Message Board: Users interact with eachother through various topics; standard message board

<a href="http://imgur.com/vJ1YD2P"><img src="http://i.imgur.com/vJ1YD2P.png" title="source: imgur.com" /></a>
Store: Sell ebooks and physical copies of authors merchandise 

### Psuedocode
Home Page

```
- Use bootstrap jumbotron to spotlight stories and writers
- Jumbtron will have automatic carasel slideshow to display the featured stories and writers

Header: 
- Build out header navbar to link to stories, inspiration, chat, login and store page
- Contain (quick) search field that will capture user search query and return the desired result
- Onclick event will happen if user selects the returned result, which will bring the user to the result page
- Header will remain consistent on all other pages

Footer:
- But out footer navbar that will link to contact, FAQ and Scribo social media 
- Footer will remain consistent on all othe rpages
```
Stories Page

```
- Contain (advanced) search field that will allow users to filter results by genre, post date or author
- Search field will capture user search query and return the desired result
- Onclick event will happen if user selects the returned result, which will bring the user to the result page
- Render stories from database to display on page
```

Inspiration Page

```
- Call to api to make get request for writing prompts
- Make function that will randomize writing prompts then render writing prompts in div on page
- Below writing prompts render inspirational articles
- Add crud functionality to articles 
```
Chat Page

```
- Use gem that will provide blueprint for message board
- Have users be able to post questions and answer questions
- Posts will have full crud
```

FAQ Page

```
- Render list of frequently asked questions
- Render unqiue answer that goes along with unique question
- Answers appear on toggle when question is clicked 
```
Contact Page

```
- Render form that includes username, email and message input
- Upon submit, form will generate email to Scribo admins that is comprised of values taken from user input
```

Store Page

```
- Use gem that will provide blueprint for store
- Render various items that the authors are selling
- Allow store items to be filtered by price, item type and book format
```

Login Page

```
- Display div that has a button for logging in and a button for signing up
- Upon click of specific button either login form or signup form will be toggled down 
```

### User Stories

### ERD

### Hurdles

### Approach Taken

### MVP
- Search feature by genre, author, post date, etc.
- Random prompt generator
- Jumbotron on homepage with spotlighted writers, stories and prompts campaign
- Login Authentication
- Shopping Cart/ Bookstore 
- CRUD for stories
- Mobile responsive

### Beyond MVP
- Ability to share stories on social media
- Message board 
- Authentication using social media 
- User profiles for authentication
- Feature to display random stories like Google feeling lucky feature

### Techonologies Used
- Ruby on Rails
- Devise 
- PostgreSQL
- Bootstrap
- Spree
- HTML/CSS/JavaScript
- Thredded

### Installation Instructions
