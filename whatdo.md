react.yml working 

app --- change port, react is using 3000

k8 cluster for react app 
either include the namespace in the yml, or apply through kubectl
yml for frontend - react - configure port? 
yml for backend
yml for db
    - secret 
yml for adminer 

dockerfile for each - need an image from yml files

backend and ap from basic 3 functional
react app from react-app


react app dockerfile created 
run with 
docker run -p 8000:3000 myapp:works

set up environment variables in backend?


k8 react app using locally run backend