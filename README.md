This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts
Build Project

### 
    docker build -t docker-react .
   
In the project directory, you can run:

### 
    docker run -it \
       -v ${PWD}:/usr/src/app \
       -v /usr/src/app/node_modules \
       -p 3000:3000 \
       --rm \
       -d \
       docker-react

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
