# Aeolus-react-typescript

## Description<br>

Aeolus is a fullstack weather application. It implements a full functional login system to personalise the experience. For the purpose above, its backend created using ExpressJS, MongoDB as its database and JWT.js for authentication purposes. As for its frontend a combination of ReactJS with **TypeScript** gets the job done. The tech stack i used, comes somewhat under the MERN stack.

## Frontend<br>

## Technologies Used<br>

* React JS
* TypeScript
* JWT.js 
* react-router V5 for routing 
* axios for backend and api calls
* SASS
* Chart.js 
* react-icons

## Instalation<br>

Create a react app with typescript template using node.js

```
react npx create react app --typescript

```
Install dependencies

```
npm install   react-chartjs-2 chart.js react-icons react-router-dom@5 axios react-jwt

```


## Backend<br>

An Express.js on top of node.js provides the main backend framework. MongoDB is used to store user infrormation and mongoose helps for the object modeling.

## Technologies Used<br>

* Express JS
* MongoDB
* mongoose
* cors to make calls to our own backend server from *only* our frontend, since frontend and backend are in different ports.
* bcrypt for hashing passwords
* dotenv

## Instalation<br>

```
npm install --save express bcrypt cors mongoose dotenv

```

## Testing<br>

Not completed section, currently working on.

* jest
* jest-dom
* react-testing-library


```
npm install --save-dev @testing-library/react jest @types/jest

```



