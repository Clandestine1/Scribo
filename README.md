# Scribo  
###### I write

### Screenshot

### Links

### About
Scribo is a judgement free platform that connects aspiring writers with other writers and bibliophiles that want to read a story. Writers can use this app to get advice from other writers on the message board, get random writing prompts, post their stories and sell their stories in the BookStore. Anyone can read a story or create a story, but only logged in users can create, update and delete posts tied to their account.

### Wireframes

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
Stories
```
- Contain (advanced) search field that will allow users to filter results by genre, post date or author
- Search field will capture user search query and return the desired result
- Onclick event will happen if user selects the returned result, which will bring the user to the result page
- Render stories from database to display on page
```

Inspiration

```
- Call to api to make get request for writing prompts
- Make function that will randomize writing prompts then render writing prompts in div on page
- Below writing prompts render inspirational articles
- Add crud functionality to articles 
```
Chat

```
- Use gem that will provide blueprint for message board
- 
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
