---
layout: single
title: Projects
permalink: /projects/
gallery:
  - url: /assets/images/YFParse.png
    image_path: /assets/images/YFParse.png
    title: "Parsing and downloading online recipes in JSON format."
  - url: /assets/images/YFEdit1.png
    image_path: /assets/images/YFEdit1.png
    title: "Editing recipe ingredients through intuitive UI"
  - url: /assets/images/YFEdit2.png
    image_path: /assets/images/YFEdit2.png
    title: "Editing recipe ingredients through intuitive UI"

gallery2:
  - url: /assets/images/MLStart.png
    image_path: /assets/images/MLStart.png
    title: "Dragging and dropping circuit components and hooking up wires."
  - url: /assets/images/MLRun.png
    image_path: /assets/images/MLRun.png
    title: "Running the circuit and seeing the critical path."
  - url: /assets/images/MLDelete.jpg
    image_path: /assets/images/MLDelete.jpg
    title: "Deleting circuit components."

gallery3:
  - url: /assets/images/SWFStart.png
    image_path: /assets/images/SWFStart.png
    title: "Joining a session."
  - url: /assets/images/SWFSearch.png
    image_path: /assets/images/SWFSearch.png
    title: "Searching and adding music to the session playlist."
  - url: /assets/images/SWFPlay.png
    image_path: /assets/images/SWFPlay.png
    title: "Listening to music on the session playtest."


---

Below is just a quick overview of some of the projects that I've worked on. I'm looking forward to watching this list grow!

## Space Zoologist
<img src="/assets/images/SZ1.png" alt="drawing" width="500px"/>

Space Zoologist is my current longest and biggest project that I’ve been working on since the start of 2020. From the very beginning I saw a unique opportunity to work on a very interesting project long term, and since then I’ve had the opportunity of being a developer, project manager, and now my current role, lead developer. I’ve learned so much about the SDLC, project management, and the planning, collaboration, and execution that goes into developing software and plan on writing up a longer post in the future about my experiences on this project.

[Try Demo!](https://louielab.org/SpaceZoologist/)

## YumFun

{% include gallery caption="Downloading and editing online recipes." %}

YumFun was developed as a final project for my IOS development class. I worked together with 4 other developers and our only specifications were to make a unique app that had a ‘magic moment’--some special moment that would impress the average user. I created one of these magic moments in the form of an automatic recipe parser which is shown in the first picture above--I parsed recipe details into JSON format and then I setup a UI which allowed the user to go through and modify the recipe as desired. I then further refined the UI through user testing and was really happy with how it turned out! We utilized Xcode, CocoaPods for various libraries, and Firebase for the backend.

## Mobilogic

{% include gallery id="gallery2" caption="Adding, running, and deleting circuits" %}

I implemented the drag and drop functionality, wire connection UI and logic, and reviewed and merged all pull requests between feature branches for this android circuit design app. We were a team of 6 developers and we utilized the Codename One framework for this project.

## Song With Friends

{% include gallery id="gallery3" caption="Joining a session, searching for songs, and playing songs in sync." %}

This was a really fun full-stack web project in which I utilized React for the frontend and NodeJS and SQLite for the backend. I also integrated the Spotify API to search and queue song requests and then play and pause songs simultaneously for multiple logged in users. I collaborated with one other developer on this project and had a ton of fun actually using this with friends!


