
# MyDiary
MyDiary is an online journal where users can pen down their thoughts and feelings. A user create an account and Enter  a space he will be able to keep his daily thoughts and stories.

# Features

- Users can create an account.
- User can sign in.
- Users can view all entries to their diary.
- Users can view the contents of a diary entry.
- Users can add entry.
- Users can modify an entry.
- Users can delete an entry.
  

### API Deployment

API Endpoint is hosted [Here](https://my-diary01.herokuapp.com/api/v1)

## Technologies

* [NodeJS](https://nodejs.org/) - JavaScript Runtime Environment
* [ExpressJs](https://expressjs.com/) - A Minimal  Web Application Framework

## Getting Started

 ### Prerequisites

 Ensure you have NodeJS installed on your computer by entering  `node -v ` on your terminal. If you don't have NodeJS installed go to the [NodeJS Website](https://nodejs.org/en/download/), and follow the download instructions
 
### Installation

Clone the app
* ``` git clone https://github.com/Le-Young/my-diary```

Install all the packages
* ``` npm install ```

Run the server
*  ``` npm start ```

## Testing
Run Test case
* ```npm run test```

Test Api 
* [Postman](https://getpostman.com/)



## Working Routes
|	Endpoint	             | Functionality         |
|------------------------|:---------------------:|
|GET /entries            | Fetch all entries     |   
|GET /entries/:id        | Fetch a single entry  |
|POST /entries           | Create an entry       |
|PATCH /​entries​/:id      ​| Modify an entry       |
|POST /auth/signup       | Regitser a user       |
|POST /auth/login        | Login a user          |
|DELETE /entries/:Id     | Delete a user Entry   |
