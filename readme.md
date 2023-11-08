# Project Name
Spotify Website with Hand-Tracker

## Description
This is a class project where I created a Spotify Music Browser webpage that collects data from the Spotify API and developed a frontend interface using Angular. The web application allows users to search for artists, albums, and tracks by communicating with a backend server written in Node.js/Express, enabling them to explore music on Spotify. Additionally, I integrated gestural control functionality using the Handjack.js library, enabling users to interact with the webpage using hand gestures.

## Technologies
HTML, CSS, JS, Jquery, Angular, Node.js, Handjack.js 

## Installation
**Setting up your Workspace:** 
Install the Angular CLI globally:
> **`npm install -g @angular/cli`** 

You will also need to install the dependencies for both the **webserver** and the **client**. These dependencies are defined in each project’s respective **`package.json`** files.

> **`npm install`** 

**Running the Webserver:**
In **`client_secret.json`** add the *clientid* and *client_secret* from your Spotify Developer account
>{
	 "client_id": "Your Client Key",
	  "client_secret": "Your Client Secret"
}

Make sure you have dependencies install by running:
>npm install

Then, to run the server with:
> npm start

**Running the Client:**

>ng serve --open 

NOTE: '--open' is optional



## Usage
- 1 open hand, 1 close hand: open artist page on Spotify
- 1 pointing, 1 close hand: open artist track on Spotify

## Launch
It can run on any web browser, but for the best display, use Google Chrome.
