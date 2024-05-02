# docker_sample
A simple docker script that os used to dockerise a python application

sample docker file for below application:


Project_Directory
│   ├── app/
│   │   ├── main.py
│   │   ├── .env
│   │   ├── other_filr.txt
│   ├── data_poc/
│   │   ├── prompts/
│   │   ├── sessions/
├── requirements.txt


to build image: docker build -t sales_commerce_app .
to run container: docker run -d -p 8787:8787 --name sales_commerce_container sales_commerce_app
