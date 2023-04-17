## First SWE-2 Task for the year 2023
This task was meant to teach you containerizing a laravel project to be able to use it in the final project so no emphasizing on the functionality

## Task Requirements
* Build a fully functional laravel project that can :
    * View all a list of names
* Containarize the project in a docker image
* Host the image on your own dockerhub account
* Submit the Github repository and the Dockerhub image links in this [form](https://forms.gle/eb7BsTdVPqCtwe9J6) 

## Tech Stack

**Client:** Blade, Bootstrap

**Server:** Apache, Laravel

**Containerization Service:** Docker

**Miscellaneous:** Github Actions, [Build and push Docker images](https://github.com/marketplace/actions/build-and-push-docker-images), [Docker Login](https://github.com/marketplace/actions/docker-login)

## Lessons Learned

* How to manage a docker image with multiple dependencies
* Containrization in Apache Server and how it works
## Run Locally

Clone the project

```bash
  git clone https://github.com/ZodicSlanser/Learning-Containrization.git
```

Go to the project directory

```bash
  cd Learning-Containrization
```

Install dependencies

```bash
  composer install
  npm install
```

Start the server

```bash
  php artisan serve
```
Go to the following route

```
http://[ContainerIP]:80/ViewStudents
```


