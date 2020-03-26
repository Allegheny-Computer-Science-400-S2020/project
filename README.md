
# cs400-S2020-project-starter

![OSLogo](400.png)

Designed for use with [GitHub Classroom](https://classroom.github.com/), this repository contains the starter files for the lab of this course.

## Objectives
To investigate a concept or mechanism that plays an important role or function in an operating system (OS). A report is to be written where the concept and its mechanism are fully explained and may be used as a learning experience for others. Source code is also to be written to complement the work and to demonstrate some specific functionality, in connection with the concept or mechanism. The report and code, combined, will serve to educate others about your investigation and provide an intelligent source of information from which the excitement stemming from concept or mechanism can be easily recognized. Note: This project should contain the same amount of work as about three labs and will not include a presentation.

## Testing your programs
This assignment uses [Docker](https://www.docker.com) to compile and run C programs without installing C compiler locally.
First, you need to make sure you have installed [Docker
Desktop](https://www.docker.com/products/docker-desktop) and have it running.
Next, you need to build the Docker container by running the following command in the terminal. Be sure that you have the ```Dockerfile``` in the local directory.
`docker build -t gccdev .`
Then, you can run the Docker container using the following command:
`docker run -it gccdev`
Now, you can mount the local drive and run the container :
`docker run -it --mount type=bind,source=$PWD,target=/home/gccdev gccdev`
Finally, you can use `gcc filename.c -o filename` to run your C program named `filename`

## GatorGrader
There is no GatorGrader requirement for this work.


## Assistance

If you are having trouble completing any part of this project, then please talk with either the course instructor or a tech-leader during the lab session. You can also schedule a meeting during the course instructor's office hours.
