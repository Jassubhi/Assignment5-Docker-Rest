# Assignment5-Docker-Rest

Created a Python RESTful services using flask and running this application using Docker.
Docker for windows home has been installed.
Open the docker terminal. 
Give the application folder path.
Build the docker image using the command:
     docker build -t app .
Once the image is created, we have to assign the port to run it using below command:
     docker run -d -p 12000:5000 app
Open the web browser and give the link:
    http://192.168.99.100:12000/
It will display the first page of the app.
   http://192.168.99.100:12000/cars ---display the list of cars.
   http://192.168.99.100:12000/cars/<id> ---display the car of particular given id.
   http://192.168.99.100:12000/cars/<id>/colors ---display the colors available of the car.
   http://192.168.99.100:12000/cars/<id>/colors/<1/2> --- display the particular selected colors.
