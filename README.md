# SLADE

![logo](https://github.com/l-yang-05/SLADE/blob/master/client/public/slade3.png)

SLADE is an MERN application that eases the grading process for military instructors. I created this application with my team at 
Hack Duke 2019. SLADE is meant to be viewed on a tablet or phone since military instructors will have to view the app on the
tablets they are given. This is for ease when going out into training instead of them using paper and pencil. When the user
opens up the application, they will be greeted with a login screen. We are using auth0 to authenticate the application. After
the user logs in, they will be given a navigation screen. There are three other main pages to the application which are the
profile for the teacher, a page for searching students, and a page that will allow them to record data. Each of the students
have a profile of their own and will display their growth over time in the program. There are charts implementing in their
profiles that will take in data from the MYSQL database we created. 

## Getting Started

Clone or download this repo onto your local machine. Once you have done this, install the node packages. You can do this by 
running ```npm i``` on your command line tool.

## Running the app

After you have installed all of the dependencies that are needed for this project, you can open the project up through your command line tool. First be in the root of the directory and then run ```npm run start``` in your command line tool. This will start the server and the react app at the same time.


## Stopping the app

To stop running the server and the react app, you can hit ```control + z``` to close both.

## Built With

* [React](https://github.com/facebook/react) - The framework used
* [NodeJS](https://github.com/nodejs/node) - The development for server
* [Express & Express Router](https://github.com/expressjs/express) - Used to create endpoints
* [Morgan](https://github.com/expressjs/morgan) - Logging tool
* [Helmet](https://github.com/helmetjs/helmet) - Provided security
* [Concurrently](https://github.com/kimmobrunfeldt/concurrently) - Used to run servers at the same time
* [MYSQL](https://www.mysql.com/)


## Author

* [Lucy Yang](https://github.com/l-yang-05)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
