# Trello_quora
REST API's have been developed as a part of an assignment

Problem Statement:  In this project, you will work on developing REST API endpoints of various functionalities required for a website (similar to Quora) from scratch. In order to observe the functionality of the endpoints, you will use the Swagger user interface and store the data in the PostgreSQL database. Also, the project has to be implemented using Java Persistence API (JPA).

UserController

signup - "/user/signup"
signin - "/user/signin" 
signout - "/user/signout" 

CommonController

userProfile - "/userprofile/{userId}" 

AdminController

userDelete - "/admin/user/{userId}"

QuestionController

createQuestion - "/question/create" 
getAllQuestions - "/question/all" 
editQuestionContent - "/question/edit/{questionId}" 
deleteQuestion - "/question/delete/{questionId}" 
getAllQuestionsByUser - "question/all/{userId}"

AnswerController

createAnswer - "/question/{questionId}/answer/create" 
editAnswerContent - "/answer/edit/{answerId}" 
deleteAnswer - "/answer/delete/{answerId}" 
getAllAnswersToQuestion - "answer/all/{questionId}"


