# React.js Installation Guide for Students

## Introduction

React.js is a popular JavaScript library for developing user interfaces, primarily in single-page applications. The aim of this tutorial is to assist you in creating your first React application as well as setting up your development environment.

The goal of this tutorial is to quickly get you off the ground with React concepts. This tutorial has hands-on exercises which I consider to be the most important part of this tutorial.

- **Here is the link to** [**React.js installation video**](https://youtu.be/kVeOpcw4GWY?si=hgEHwgGAUfckm_Tv)

**Step by step installation guideline:**

## **1\. Installing Node.js and npm**

Node.js and NPM (Node Package Manager) are required to install and manage React and its dependencies.

### Download and Install Node.js

1. Go to the [Node.js download page](https://nodejs.org/).
2. Download the LTS version (Long Term Support) for your operating system.
3. Run the installer and follow the setup instructions.

![](https://www.freecodecamp.org/news/content/images/2020/10/nodejs.png)

### **Verify Installation**

After you download and install Node, start your terminal/command prompt and run node -v and npm -v to see which versions you have.

![](https://www.freecodecamp.org/news/content/images/2020/10/t1.png)

## **2\. Creating a React Application**

You can create a React application using the Create React App tool, which sets up everything you need.

### Create React App

1. Open your terminal.
2. Navigate to the directory where you want to create your project.
3. Run the following command to create a new React application:

**npx create-react-app my-app**

Replace **my-app** with your desired project name.

1. Navigate into your project directory

**cd my-app**

## **3\. Running the React Application**

1. Start the development server by running the following command in your project directory:

**npm start**

1. Open your web browser and go to <http://localhost:3000>. You should see your React application running.

![](https://www.freecodecamp.org/news/content/images/2020/10/rw.png)

If you see something like this in your browser, you are ready to work with React. Congratulations! :)

## **4\. Project Structure Overview**

Here’s a brief overview of the files and directories in a new React project:

- **node modules/**: Contains all the dependencies and modules installed.
- **public/**: Contains the public assets of the application, including the **index.html** file.
- **src/**: Contains the React components and other source code.
  - **App.js**: The main component of your application.
  - **index.js**: The entry point of your React application.
- **package. Json**: Contains metadata about your project and lists dependencies.
- **package-lock. Json**: Locks the versions of your dependencies.

If you face any problems with anything mentioned in the articles above, feel free to discuss it on the WhatsApp group.

Stay tuned for React.js tutorials coming next week!

Created with ❤️ by [WnCC](https://itc.gymkhana.iitb.ac.in/wncc/)
