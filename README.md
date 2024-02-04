# Mod19-ProgWebApp-TextEditor
Task is to build a text editor that runs in the browser. Single-page application that meets the PWA criteria. Will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. Will also function offline.


## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contact Information](#Contact)


## Description

A single-page text editor that meets the PWA criteria, runs in the browser, and functions offline. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.

### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation
 
Install to your local machine.

Clone this repository to your local machine.

Right click on package.json and select "Open in Integrated Terminal"

There should be a package.json file included. To install the various npm packages used run the command

```md
npm i
```

## Usage

Visit the deployed site below. When you enter text it will save automatically when you click off of the window. If you refresh or revist the text will remain. If you go offline it will store your changes until you are back online. It is downloadable as a separate app.

### Deployed Site
https://pwa-with-jate-bdca3d62036d.herokuapp.com/


<video src="TEXT%20EDITOR%20MOD19.mp4" controls title="Title"></video>

### Screenshots

![Web page in browser](/assets/1.png)

![Install button in browser](/assets/2.png)

![Install box](/assets/3.png)

![Installed on local machine](/assets/4.png)

![cache storage](/assets/5.png)

![Inspect](/assets/6.png)




## Credits

Webpack

https://webpack.js.org/



## License
MIT License

Copyright (c) 2024 Shan Nowak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contact

This app was created by Shan Nowak.

Contact:

GITHUB: https://github.com/scnowak

EMAIL:  SHAN.NOWAK93@GMAIL.COM
