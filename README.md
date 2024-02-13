# Dockerizing Flask with Postgres, Gunicorn, and Nginx

## Overview

In this project, I made a web app that allows the user to upload an image (both static and media) from their computer and view it in their browser. 
I followed [this tutorial](https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/) in order to dockerize Flask and create a fully working web service to emulate Instagram's tech stack.  

Once the container has been successfully built and run, the user can upload an image by visiting [http://localhost:<port>/upload](http://localhost:<port>/upload)

And view it at: [http://localhost:<port>/media/IMAGE_FILE_NAME](http://localhost:<port>/media/IMAGE_FILE_NAME)


## Demo
![gif of image upload](https://github.com/lbielicki/flask-on-docker/blob/media/bigdata_instagram_final_gif.gif)


## Build Instructions

