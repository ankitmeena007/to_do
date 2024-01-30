# To Do List

## Built using HTML, CSS, Javascript and EJS
## requirements: Node.js, Mongodb atlas account
## Database used: Mongodb
## Hosted on: Vercel

*Also features custom list creation.


## Live working [demo](https://to-do-007.vercel.app/) 

![image](https://github.com/ankitmeena007/to_do/assets/63893740/3c5bc120-2ecb-4042-b1fa-c08642734f77)


# To build your own To Do List:

1. Create a MongoDB Atlas account and obtain connection string
   See this [tutorial](https://www.mongodb.com/docs/guides/atlas/connection-string/) for more info.

2. Fork or Clone
   Fork or clone this repo.

3. Create .env file
   > create `.env` file at the root of project
   
   > inside .env file add `DB_CONNECT` as env variable and paste your MongoDB Atlas connecting string:

```
// For example
// .env

DB_CONNECT = <your connecting string>
```
Note: if adding .env to .gitignore file at root of the project doesn't hide the .env file for some reason, then you can use the following commands:

```
git rm -r --cached .env

git add .
git commit -m 'your message'
git push
```


Credits : - [Web Dev Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp)
