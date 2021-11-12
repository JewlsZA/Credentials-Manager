# Setup Credential Manager

To run the program on your system you would need to install React and Node.js
Here is a quick guide to get you started: https://www.freecodecamp.org/news/install-react-with-create-react-app/

Open the project files in your favorite IDE and Change Directory to the project in your terminal of choice.

To install dependancies run the following in the terminal.
```
npm install
```
To start your local react and express servers, navigate to the backend and frontend file directory and run the following command in the terminal.
```
npm start 
```
a Browser windows should open where you can interact with the program !
If the browser does not open type http://localhost:3000/ in your browser


# What is Credential Manager?

The programs is intended to be used internally by large companies with multiple departments and sub department to store company login credentials like Facebook and Instagram accounts. With the use of JWT users only have access to resources withing their department. Furthermore there are 3 different types of users, namely regular users, managers and admins. Regular users can access and create credentials, managers can do all the above and edit credentials where admins can also assign user departments and permissions.


# How credentials Manager works

The frontend is written in React and backend in Express. MongoDB is used as prefered Database and JWT is user for authentications. All database communications is handled by the backend. I removed the database connection information for Github public posting.

# Program limitations

Program does not validate user text inputs
