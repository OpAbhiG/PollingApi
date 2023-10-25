# PollingAPI
API for Polling Questions - Coding Ninjas Backend Skill Test Project

Task: Need to create an API where anyone can create questions with options and also add votes to it

---

# API for Polling Questions - Coding Ninjas Backend Skill Test Project

Task: Need to create an API where anyone can create questions with options and also add votes to it

## Features
Create a question
Add options to a question
Add a vote to an option of question
Delete a question → (optional: A question can’t be deleted if one of its options has votes)
Delete an option → (optional: An option can’t be deleted if it has even one vote given to it)
View a question with its options and all the votes given to it

## How to use it in your local system

1. First install the MongoDB community server on your device by going to the Mongodb website and then downloading the Mongodb community server
2. Once you download the MongoDB community server just open your terminal and run the command `npm install`
3. After running the command, it will download all the libraries needed to run this project.
4. For using This project, You need the postMan and MongoDB Compass to get the documents saved in your database.
5. Just download the MongoDB Compass and PostMan from the browser.

## How to use PostMan

1. Open PostMan
2. Enter The Url into the postMan with the required Method and data to pass with the request
3. Then just Note The Change in your database.

### URL That I Have Created

1. _http://localhost:8000/questions/create_ (To create the questions)
2. _http://localhost:8000/questions/:id/options/create_ (To create the options of particular questions)
3. _http://localhost:8000/options/:id/add_vote_ (To add a vote for a Particular Option)
4. _http://localhost:8000/questions/:id_ (To get the details about the particular question)
5. _http://localhost:8000/questions/62ff5f8d8989690a30403f31/delete_ (To delete a Particular Question)
6. _http://localhost:8000/options/62ff61c492d525ac764ec787/delete_ (To delete a particular option)


Git Repository link: https://github.com/OpAbhiG/PollingApi--Main

Hosted URL: https://polling-api-npoe.onrender.com/

## Folder Structure
```
CSV_Upload/
|── |config/
│   |      ├── mongoose.js
|   |
├── routes/
│   |      ├── api/
│   ├── index.js
|   |
├── controllers/
│   ├── OptionsController.js
│   ├── QuestionsController.js
|   |
├── models/
│   ├── options.js
│   ├── questions.js
|   |
├── package-lock.json
├── package.json
├── README.md



## _Note_

1. A question can’t be deleted if one of its options has votes
2. An option can’t be deleted if it has even one vote given to it
