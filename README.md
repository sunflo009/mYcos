# Enigma
A minimal brain game for all ages, written by angular - [check out the demo](http://enigma.apphb.com/)

## How to play
complete the mission by rotating all roters to show the same green light, Easy!


![enigma demo](https://sv1.picz.in.th/images/2019/10/09/cCk0aq.gif)

## How to install

1) Install Angular CLI  
> `npm install -g @angular/cli`

2) Install Packages
> `npm install`

3) Start Site
> `ng serve`

# Enimg Api

The enigma api develop using asp.net core 2.2

## Prerequisite

> Install .net core sdk : [Windows](https://dotnet.microsoft.com/download/visual-studio-sdks) | [Mac](https://dotnet.microsoft.com/download/dotnet-core/2.2)

## Setup and install
Try to open the project using Microsoft Visual Studio and build the project

**To restore and setup database**
For command line terminal, go to the directory of the project ***Api.Enigma*** and enter this command

    dotnet ef database update
For **Package Manager Console** in visual studio enter this command

    Update-Database

## Run the app
Using Microsoft Visual Studio click on **Run** button
![enter image description here](https://sv1.picz.in.th/images/2019/10/21/cMQFhQ.gif)

And go through : *http://localhost:5000/swagger/*
