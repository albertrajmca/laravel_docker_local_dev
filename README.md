# laravel_docker_local_dev
Run Laravel, MySQL, PhpMyAdmin using docker

1. Make sure that you have a docker set up on your local machine. 

2. Docker Desktop for mac

3. Navigate to the root folder where the docker-compose.yml exists

4. Run docker-compose up --build command 

5. Wait for few minutes to build the laravel application as a image. 

6. Based on the local system availablity MySQL and PMA images will be pulled or cached.

7. Open the browser and browse [http://localhost:8100](url)


<img width="1411" alt="Screenshot 2021-11-05 at 10 33 45 PM" src="https://user-images.githubusercontent.com/17470465/140550218-c5688dcf-f834-4126-8312-a1493bc199b3.png">

8. Click on Register page and enter the required details

<img width="1429" alt="Screenshot 2021-11-05 at 10 37 15 PM" src="https://user-images.githubusercontent.com/17470465/140550558-3abf1422-2a61-4ab9-b8b6-b65be7e47611.png">

10. Click on Register at the end and it will show you dashboard page with logged in message

<img width="1400" alt="Screenshot 2021-11-05 at 10 37 49 PM" src="https://user-images.githubusercontent.com/17470465/140550655-412e3424-db6d-4476-b0ce-05ca88d7150f.png">
11. Open http://localhost:9191 to check the database with username/password => devuser/devpass

13. User table should be filled with the details what you have given


Great, success you have a Laravel application as a docker image

