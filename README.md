# Detector

[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()


> A web app to detect covid-19 with accuracy of 92%-90% from chest X-rays of patients 


## Please follow these steps to run app

- Clone this repo 
- Install requirements
- Run the script
- Go to http://localhost:5000
- Done! :tada:

:point_down: Screenshot:

<p align="center">
  <img src="/static/screenshot.png" height="480px" alt="">
</p>

------------------

## Run with Docker

With **[Docker](https://www.docker.com)**, you can quickly build and run the entire application in minutes :whale:

```shell
# 1. First, clone the repo
$ git clone https://github.com/khaledbay/Detector
$ cd Detector

# 2. Build Docker image
$ docker build -t covid19_app .

# 3. Run!
$ docker run -it --rm -p 5000:5000 covid19_app
```

Open http://localhost:5000 and wait till the webpage is loaded.

## Local Installation

It's easy to install and run it on your computer.

```shell
# 1. First, clone the repo
$ git clone https://github.com/khaledbay/Detector
$ cd Detector

# 2. Install Python packages
$ pip install -r requirements.txt

# 3. Run!
$ python app.py
```

Open http://localhost:5000 and have fun. :smiley:

<p align="center">
  <img src="/static/screenshot.gif" height="480px" alt="">
</p>

------------------

## Future

1) Enrich the dataset with another real cases.
2) Improve the detection accuracy.
3) Hosting the app. 

 


