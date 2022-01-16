# Docker + NodeJS

An example of ExpressJS server as Backend with docker environment setup.

## Installation

NodeJS should be installed in your local machine with npm package then run the below command in the project working directory.

```bash
npm i --save
```
After finishing the installation node_modules should be added to your project. 

Also, you have to install [Docker](https://www.docker.com/) on your local machine.

## Running the App

#### 1- Build the image
```bash
docker build -t <image-name>:<version> .
```
#### Example 

```bash
docker build -t khattab/node-js-docker:1.0 .
```
#### After building the image successfully, you should run the container for this image as below: 

```bash
docker run -p 5000:8080 <image-id> .
```
#### Check the docker GUI to get the image id and then replace it with the above <image-id>

#### Now it should work fine, open your browser and enter 

```http://localhost:5000```

