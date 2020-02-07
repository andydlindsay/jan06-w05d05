# W5D5 Mid-term Project Kickoff Planning

## don't code today
## destroy the repo

- front load the work
- 

- Friday noon
- CS presentation afterwards

### Where do we start?
- pick a project

### User Stories
- tweeter example user stories
- As a ______, I want to ______, so that I can ________
- As a user, I want to be able to save posts, so that I can view them again in the future.
- user scenario
- Given _____, when _____, then _____
- Given that I am logged-in user, when I click to favourite a post, then it is saved to my favourites

### Nouns === Table Names
- users, posts, favourites

### Data is the most important thing
- What is the data that I have access to?
- Where does it come from? user(s), external API
- Can you correlate this data into something useful?

- data is the foundation of the application

### MVP
- Minimum Viable Product
- Create an app with the minimum amount of features that will make it useful to a user
- Minimum Viable Demo
- If you're not going to demo it, DON'T BUILD IT
- about, faq

### Mentor review
- ask multiple mentors
- opinionated

### Routes/API Endpoints
- RESTful API
- BREAD operations on your resources
- mentor review

GET /users/:id/favourites
GET /posts/:id/favourites

GET /users
DELETE /users/:id

users, posts, favourites

### Wireframes
- build 'em
- use a whiteboard

### User Login
- Don't do it

```js
app.get('/login/:id', (req, res) => {
  req.session.user_id = req.params.id;
  res.redirect('/');
});
```

### Tech Choices
- Stack/Frameworks
- Back end: Node && Express
- Front end: HTML, CSS, JS, jQuery, Bootstrap, SCSS, Foundation Zurb






#
