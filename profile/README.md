# Software development exercises

This organization contains repositories for exercises related to software development courses at Haaga-Helia University of Applied Sciences. Most exercises have automated tests that are designed to work with GitHub Classroom. The exercises cover various topics, including DevOps, Docker, TypeScript, testing, and more.

Most of the repositories are in Finnish, as the courses are primarily taught in Finnish. Some repositories may contain English instructions or documentation. The exercises are intended for educational purposes and may not be suitable for production use. Exercises are provided "as is" without any warranties, although we appreciate feedback and ideas on how to improve them.


## Docker (and Linux)

* https://github.com/harjoitukset/linux-commands

    This repository contains exercises for familiarizing yourself with Linux commands.

* https://github.com/ohjelmistokehitys/docker-commands

    In this exercise, you will create a Docker container and practise running basic commands both inside the container and on the host system.

* https://github.com/ohjelmistokehitys/dockerfile-exercise

    This exercise will guide you through the process of containerizing a web application using Docker. You will learn how to create a Dockerfile, build a Docker image, and run a container from that image.

* https://github.com/ohjelmistokehitys/docker-compose-postgresql

    The goal of this exercise is to get acquainted with the key concepts and features of Docker and Docker Compose, such as volumes, ports, and environment variables. At the same time, you will work with real tools like PostgreSQL and pgAdmin.

* https://github.com/ohjelmistokehitys/monitoring-logging

    This exercise will introduce you to centralized logging and monitoring of applications. Logging and monitoring are essential parts of modern software development and operations, as they help in understanding application behavior, diagnosing issues, and ensuring system reliability.

* DevOps with Docker (mooc.fi)

    The following repositories contain automated tests for the DevOps with Docker course on mooc.fi: https://courses.mooc.fi/org/uh-cs/courses/devops-with-docker.

    * https://github.com/ohjelmistokehitys/docker-part-1a
    * https://github.com/ohjelmistokehitys/docker-part-1b
    * https://github.com/ohjelmistokehitys/docker-part-2a


## Git

* https://github.com/ohjelmointi2/git-hello-world/

    In this exercise you learn the basics of Git version control. Before starting the exercise, make sure you have installed the Git tool for your computer and done the required setup for Git. You will also need a GitHub account.

* https://github.com/ohjelmistokehitys/git-multiplayer-exercise

    The goal of this exercise is to make minor modifications to a codebase and practice using Git in a collaborative environment. The exercise is designed to be used in a classroom setting, not as an assignment to be completed individually.

* https://github.com/ohjelmistokehitys/merge-exercise

    This repository contains a simple React-based countdown timer application built with Vite. Several features of the application have already been implemented, each of them in a separate branch. The goal of this exercise is to merge these branches into the main branch using Git.


## Test automation

* https://github.com/testiautomaatio/getting-started

    The goal of this exercise is to install the Playwright testing library and learn how to run and develop tests using Playwright.

* https://github.com/testiautomaatio/authentication-tests

    The purpose of this exercise is to write your first tests using the Playwright tool. You will test the functionalities of a simple website, such as logging in and registering. The goals are to learn how to perform operations like entering text and clicking buttons, as well as checking results.

* https://github.com/testiautomaatio/interaction-playground-tests

    In this exercise, you will continue practicing with Playwright and test the functionalities of a website. The focus is on locating different types of elements and interacting with them, such as text fields, buttons, and error messages.

* https://github.com/testiautomaatio/robot-browser-devcontainer

    This repository provides a development container that includes all the necessary tools and dependencies for using Robot Framework and the Browser library. The container is configured to work with Visual Studio Code's Remote Containers extension, allowing you to develop and run tests in a consistent environment without worrying about local setup issues. This container works both in local development using Docker or in GitHub Codespaces, which provides a cloud-based development environment. 

* https://github.com/testiautomaatio/authentication-tests-robot/

    In this exercise, you will write tests for the same website as in the previous exercise, but this time using the Robot Framework and the Browser library. The goal is to get acquainted with a different testing tool and its syntax.

* https://github.com/testiautomaatio/robot-framework-bdd

    In this exercise, you will practice writing end-to-end (E2E) tests using Robot Framework and the Browser library. In BDD, test cases are written in natural language and describe the program's behavior from the user's perspective.

* https://github.com/testiautomaatio/rpa-exercise

    In this exercise, you will use the Playwright tool to transfer data from an old system to a new one. The transfer is carried out by automating steps that would take a lot of time and be prone to errors for a regular user. Such a solution is often called "software robotics" or Robotic Process Automation.


## TypeScript, Node.js and NPM

* https://github.com/harjoitukset/typescript-postalcodes

    The goal of this coding exercise is to create a foundation for the following tasks, where we will handle data and test software using TypeScript.

* https://github.com/harjoitukset/typescript-users-and-posts

    In this exercise, you will practice defining and using TypeScript types as part of program logic in a Node.js environment. The task is to read users and posts from two separate JSON files and match users to their corresponding posts.

* https://github.com/harjoitukset/typescript-users-and-posts-v2

    In the first part of the task, you got acquainted with TypeScript and the solution style was free. This time, our goal is to learn certain pre-selected algorithms and data structures, and to make the code testable and reusable.

* https://github.com/ohjelmistokehitys/async-music-webapp

    This exercise focuses on using REST APIs in a React application, handling asynchronous operations, and properly managing loading states.

* https://github.com/ohjelmistokehitys/serverless-color-converter

    In this exercise, you will learn to utilize the Hono application framework and implement functions that handle HTTP requests and responses, but are not dependent on a specific server environment.

* https://github.com/ohjelmistokehitys/node-package-exercise

    In this exercise, you will learn to create and work with npm packages. Npm (Node Package Manager) is a package management system that comes with Node.js, enabling the installation and management of third-party libraries and tools in your projects.

* https://github.com/ohjelmistokehitys/graphql-routeplanner

    This exercise combines the use of REST APIs and GraphQL interfaces with TypeScript. The project builds a very simplified version of a route planner that utilizes Digitransit's location data and routing services. See live demo at https://ohjelmistokehitys.github.io/graphql-routeplanner/.

* https://github.com/ohjelmistokehitys/mqtt-map/

    This exercise contains a React application that displays real-time traffic data on a map using the Leaflet library. Students learn to interact with an MQTT broker to receive real-time data and update the map accordingly. See live demo at https://ohjelmistokehitys.github.io/mqtt-map/.


## Java

* https://github.com/ohjelmointi2/warming-up

    This repository contains a set of Java exercises that will help you review the content of the Programming 1 course and familiarize yourself with the technical implementation of the exercises for the advanced course.

* https://github.com/ohjelmointi2/map-exercises

    With this exercise package, you will learn to utilize the Map data structure in your own applications.

* https://github.com/ohjelmointi2/junit-exercise

    This repository contains Java exercises to practice unit testing with the help of the JUnit tool. Unlike previous exercises, this task does not have pre-written tests; you will write the tests yourself. However, the Java classes to be tested are already in the project template.

* https://github.com/ohjelmointi2/inheritance-interfaces

    This repository contains a set of Java exercises to help you get acquainted with inheritance and interfaces.

* https://github.com/ohjelmointi2/streams-and-lambdas

    In this task repository, you will explore Java's Stream API and lambda expressions. The exercise is divided into parts, each containing a Java class with incomplete methods. Your goal is to complete the logic of these methods using streams and lambdas.

* https://github.com/ohjelmointi2/sql-databases/

    In this exercise, we will learn how to connect to a database from a Java program and perform simple CRUD operations (Create, Read, Update & Delete). Along the way, we will get acquainted with concepts such as JDBC, DAO, and PreparedStatement.

* https://github.com/ohjelmointi2/sorting-and-filtering

    In this task, we will explore filtering and sorting lists of Java objects based on different attributes.

* https://github.com/ohjelmointi2/commit-history/

    This final course assignment repository contains various exercises designed to deepen and apply the topics from previous weeks. You have more freedom in solving these tasks, so you can approach them in many different ways.

* https://github.com/ohjelmointi2/wordplay-exercise

    The purpose of this exercise is to familiarize yourself with various data structures and algorithms, particularly from the perspective of their performance.

* https://github.com/ohjelmointi2/generics-and-sudoku/

    With this exercise package, you will learn to define generic methods and classes. The topic is initially covered by creating general-purpose methods that can handle different types of data without having to repeat the program logic for different types.


## Python

* https://github.com/python-ohjelmointi/autograding

    A collection of scripts and tests for automatically testing and grading exam submissions returned in MS Teams.

* https://github.com/python-ohjelmointi/harjoituskoe

    This repository contains a set of exercises for practicing Python programming to prepare for a course exam. The exercises can be automatically tested using doctests, which are included in the code files.
