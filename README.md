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

# Screen Shots of the Output - Swagger UI 
![swagger-apis-output](https://user-images.githubusercontent.com/47784012/54137352-87999e00-4443-11e9-9dc6-c3ed11aba2ed.JPG)
![swagger-apis-list1](https://user-images.githubusercontent.com/47784012/54137378-92ecc980-4443-11e9-8646-85b8cd6bdaec.JPG)
![swagger-apis-list2](https://user-images.githubusercontent.com/47784012/54137384-9718e700-4443-11e9-87c6-9f146c53d0aa.JPG)
![eg-signin-api](https://user-images.githubusercontent.com/47784012/54137390-9aac6e00-4443-11e9-9d92-5a7033ba4e86.JPG)

