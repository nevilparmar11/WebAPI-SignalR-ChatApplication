# Chat App
A real-time chat application using WebAPI & SignalR. Available for Web and Desktop.

## Features
* Group chat
* Private chat `/private(Name) Hello, how are you?`
* Photo message
* Basic Emojis
* Chat Rooms

## Technologies used
1. WPF(Windows Presentation Foundation) in C#
2. ASP.Net Core Web API
3. SignalR
4. ASP.Net Framework
5. SQL Server Database
6. Bootstrap
7. Javascript

## Implementation Details
The project solution contains 2 projects. <br>
![solution](https://user-images.githubusercontent.com/48133426/113412361-a629b380-93d5-11eb-8df1-3c0cb24713b9.jpg)


1. Chat.Web
- WEB API Project
- The project contains services and Hubs implementation related to chat operations and users management
- It uses Signal-R for real time update in chat
2. Chat.Desktop
- WPF desktop client to demonstrate use of single service in different platform

## Getting Started
In order to run Desktop application you need first to run Chat.Web project which is the Chat Service

1. Grab the Project
2. Open Visual Studio as Administrator and load the Solution
3. Resolve any missing/required nuget package

### For Chat.Web
1. Build Database. Open `Package Manager Console` and run the following commands: <br />
`update-database` <br />
2. That's all... Run the Project!

### For Chat.Desktop
1. Run the desktop application: `Right-Click -> Debug -> Start new instance`


## UI 💻
<img src="https://user-images.githubusercontent.com/48133426/113413215-bb9fdd00-93d7-11eb-97d9-a97ebdf0623b.png" width="45%"></img> <img src="https://user-images.githubusercontent.com/48133426/113412465-fb65c500-93d5-11eb-9b76-efeaf077f7e1.png" width="45%"></img> <img src="https://user-images.githubusercontent.com/48133426/113412704-9bbbe980-93d6-11eb-82fa-72cb12ebc415.jpg" width="45%"></img> <img src="https://user-images.githubusercontent.com/48133426/113413564-98296200-93d8-11eb-8a1b-054b9df8acc9.png" width="45%"></img> 

## Live Demo
[Visit Demo](http://bit.ly/soc_webapi_demo) <br>

### The MIT License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/nevilparmar11/WebAPI-SignalR-ChatApplication/blob/main/LICENSE)  

---------

```javascript

if (youEnjoyed) {
    starThisRepository();
}

```

-----------

## Thank You
- Author : [Nevil Parmar](https://nevilparmar.me)
