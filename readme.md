## Getting started

This project was made with Anaconda (latest version) in a docker environment. To make sure that everything will work, make sure to run this project in docker or at least in a updated conda environment.

## How to execute
<p> First of all, you'll need to download the data to execute the project. It's almost 2gb of data so I decided to upload on my own S3 bucket. </p>

<p>You can download the files by clicking <a href="https://data-sprints-desafio.s3.us-east-2.amazonaws.com/data.zip">here</a></p>

<p>After download the data, put the zip in the same folder as the notebooks and extract the .zip</p>

<p>After that, just open a terminal in the same folder as your files and type: </p>


```docker-compose up```

The jupyter server will be running in localhost:8888. 
To access the notebooks for the first time, you'll need to put a token in a input, so, just put ```jupytertoken``` in that. 

You can run the notebook in your own environment, just make sure to have everything up to date. 