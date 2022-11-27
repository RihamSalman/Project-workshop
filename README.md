# App Title

Flask Application to show time in Moscow

## Description

In this part, I'm using python/flask as a framework, doing a simple webserver to show the current time in Moscow. The time is updated with a page refreshing.
here we have the following:
* app.py: the python file contain a simple function to get the time, and render the page
* requirements: it contains the important libraries which we need to download them
* template: a simple HTML file, just to make the page clear


## Getting Started

### Dependencies

* Linux/Unix OS
* Free port 8000

### Executing program
To excute the program you need to go to the  /app directory and run the following from the terminal:

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
python3 app.py
```

then check the localhost in port:8000

## Docker

- Dockerfile: dockerizing the app by building image contains the app and the requirments to run it.
- The application is hosted on a WSGI server using Gunicorn
- Our application is available through a Docker container at `rmsalman/time_in_moscow`. To run the image execute
```
docker run --publish 8000:8000 rmsalman/time_in_moscow
```


## Author 
This project is created by Riham Salman

## Contact 
email: riham.salman.98@gmail.com

