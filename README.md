# **Node.js ToDo App with Docker**

## **Project Description**

This is a simple **ToDo App** made with Node.js.
You can use the app to manage your ToDos.

The app can run locally and with **Docker**.

## **Prerequisites**

You need these programs:

* **Node.js**
* **npm**
* **Git**
* **Docker**

## **Clone the Repository**

1. Open the repository on GitHub.
2. Clone the repository:

```bash
git clone YOUR-REPOSITORY-URL
```

Then go to the project folder:

```bash
cd docker-nodejs-sample
```

## **Install Packages**

Install the needed packages:

```bash
npm install
```

## **Run the Application Locally**

Start the app with:

```bash
npm start
```

You can open the app in your browser:

[Open the ToDo App](http://localhost:3000/)

## **Build the Docker Image**

Create the Docker image:

```bash
docker build -t todo-app .
```

## **Run the Application with Docker**

Start the Docker container:

```bash
docker run --name todo-container -p 3000:3000 todo-app
```

You can open the app here:

[Open the ToDo App](http://localhost:3000/)

## **Run the Application with Docker Compose**

Start the app with Docker Compose:

```bash
docker compose up --build
```

## **Stop the Application**

Stop the application with:

```bash
docker compose down
```
