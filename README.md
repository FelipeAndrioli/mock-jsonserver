# JSON Server

## About

### Description

When the front end part of an application is being developed, the
back end is being developed in the same time. Due to this the front
end developers can't test the requsitions. To avoid this we have the 
JSON Server, that simulate a back end with database and with the
possibility to have rules. 

On this way we are able to test our requests by the browser with
"manual" requests like ```http://localhost:port/users``` or using
tools like Postman and Insomnia.

## Instructions

### How to run

In this repository you'll find a node application to run the JSON server
with some rules to not allow POST requests with duplicated values. To
run the server just run the following commands with node installed:

```npm install```
```node index.js```

## Source

### Followed tutorial

To create this simple application I follow this tutorial:

[Tutorial](https://keyholesoftware.com/2020/03/16/mock-restful-server-fast-with-json-server/)
