# Capstone_1
First capstone project

1. What goal will your website be designed to achieve?

Goal is to provide a public forum to discuss Studio Ghibli movies and be able to score movies, characters, etc. Also will act as a searchable database which will display specific information. 

2. What kind of users will visit your site? In other words, what is the demographic of
your users?

People that are fans of Studio Ghibli movies and highly opinionated. 

3. What data do you plan on using? You may have not picked your actual API yet,
which is fine, just outline what kind of data you would like it to contain.

https://ghibliapi.vercel.app/

4. In brief, outline your approach to creating your project (knowing that you may not
know everything in advance and that these details might change later). Answer
questions like the ones below, but feel free to add more information:
a. What does your database schema look like?

User         Score             Comments         Info page             User activity (link table)
id           id                id               id                    user_id  
username     score             comment          name                  score_id
password                       username         type                  comment_id
                                                                      info_id

b. What kinds of issues might you run into with your API?

API seems straightforward, no authentication needed and no request limit.

c. Is there any sensitive information you need to secure?

User credentials 

d. What functionality will your app include?

User will be able to search for movies or specific elements like characters, settings, etc. 
User will be able to score movies or specific elements like characters, settings, etc. 
User will be able to comment on info pages for movies or specific elements like characters, settings, etc. 

e. What will the user flow look like?

Register -> Login -> Search for info page -> Add score/comments -> Home page shows everything that has been scored in order, grouped by type 

f. What features make your site more than CRUD? Do you have any stretch
goals?

Maybe add a quiz before user sign up to make sure it's a true studio ghibli fan. Randomly selects a film in the database and asks a question.
Adding a CAPTCHA
Finding a way to generate images on each info page based on what is searched 
Being able to reply to specific users rather than just listing comments 
Adding thumbs up/thumbs down to comments, home page rankings, etc


