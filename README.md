# Ghibli_Forums

### Overview

The is a forums site for the Ghibli Studio Films. From the homepage, you will be able to click the individual movie images and be redirected to their own forums page. In this page, you can make your own threads and strike up engaging conversations with fellow Ghibli fans!

### Wireframe

![Wireframe](./images/Database_schema.png)
![Wireframe](./images/Ghibli_Forums_Wireframe.png)
![Wireframe](./images/Ghibli_Forums_Components_Tree.png)


### User Stories

-When I go on the site, I see the images of the movies. 

-I am able to successfully make an account or log into my account

-When I click on an image, I am able to go to the respective forums page

-I am able to write a thread and comment but an alert pops up saying I need to be logged in to post them 

-I am able to write a thread and comment and successfully post them when logged in 

-I am able to view all the threads from every forum when I view my own user page



### Routes

|Routes                     | HTTP Verb                       | URL                            |
| :----------------------: | ------------------------------- | ------------------------------- |
| movieRoute    | .get     | '/'                                  |
| movieRoute    | .get     | '/:movieId'                          |
| movieRoute    | .get     | '/:movideId/threads'                 |
| movieRoute    | .get     | '/thread/:threadId/comments'         |
| userRoute     | .post    | '/signup'                            |
| userRoute     | .post    | '/login'                             |
| userRoute     | .get     | '/verify'                            |
| userRoute     | .post    | '/:userId/thread/:movieId'           |
| userRoute     | .get     | '/userId/threads/'                   |
| userRoute     | .post    | '/:userId/thread/:threadId/comment ' |
| userRoute     | .get     | '/user/:threadId'                    |
| userRoute     | .get     | '/user/:comentId'                    |
| userRoute     | .put     | '/thread/:threadId'                  |
| userRoute     | .put     | '/comment/:comentId'                 |
| userRoute     | .delete  | '/thread/:threadId'                  |
| userRoute     | .delete  | '/user/:comentId'                    |



___
### MVP

-Navigating through forums by the click of their image 

-React User Auth

-Posting threads and comments associated with user

-Viewing threads from user page 

### Stretch Goals

-useContext

-password hashing

-like functionality of posts and comments


