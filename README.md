# accounts.susi.ai

[![Build Status](https://travis-ci.org/fossasia/accounts.susi.ai.svg?branch=master)](https://travis-ci.org/fossasia/accounts.susi.ai)
[![Twitter Follow](https://img.shields.io/twitter/follow/asksusi.svg?style=social&label=Follow&maxAge=2592000?style=flat-square)](https://twitter.com/asksusi)

SUSI.AI is an artificial intelligence combining pattern matching, internet data, data flow principles and inference engine principles. It will have some reflection abilities and it will be able to remember the users' input to produce deductions and a personalized feedback. Its purpose is to explore the abilities of an artificial companion and to answer the remaining unanswered questions. The accounts.susi.ai repo is a front-end web application that is developed for managing user accounts of SUSI.AI. The project is hosted on gh-pages at https://accounts.susi.ai.

## Communication

Please join our mailing list to discuss questions regarding the project: https://groups.google.com/group/susiai/

Our chat channel is on gitter here: https://gitter.im/fossasia/susi_server

## Technology Stack

### Components
* HTML - Structure of the web page generated.
* CSS - Styling options and details of the web page.
* Javascript(JSON) - Used to store information for deploying the application such as dependencies.
* ReactJS - Structure for deployment of the web page.

## Requirements
* node --version >= 6
* npm --version >= 3

## How to deploy?

### Running on localhost:
* **Step 1:** Fork accounts.susi.ai repository and clone it to your desktop
* **Step 2:** Then cd into that cloned folder
* **Step 3:** Install all the dependencies by running :```$ sudo npm install```
* **Step 4:** Run on http://localhost:3000 by running :```$ npm run start```
* **Step 5:** Build locally by running : ```$ npm run build ```
* **Step 6:** To deploy at a url use : ```$ npm run deploy ```

### Running on [Surge](https://github.com/fossasia/chat.susi.ai/blob/master/docs/INSTALLATION_SURGE_ENGLISH.md)

**Click this picture to see video about deploy!**
[![Watch the video](https://i2.wp.com/blog.fossasia.org/wp-content/uploads/2017/08/surge_static_hosting.png)](https://www.youtube.com/watch?v=Gvc0uz13U1M)

* **Step 1:** Install Surge:```$ npm install -g surge```
* **Step 2:** Then cd into the cloned chat.susi.ai folder
* **Step 3:** Build the app:```$ npm run build```
* **Step 4:** Go to the build directory:```cd build```
* **Step 5:** Run Surge:```surge```
* **Step 6:** Follow the prompts and provide an e-mail address and a password.
* **Step 7:** Go to the URL that appears after the above process is finished, and provide this link in the PR for testing your changes.

Still having problems? Watch this video to clear your doubts [How to setup SUSI web-chat with surge](https://www.youtube.com/watch?v=vM9cD1pHMDQ&t=240s)

### Colours and Font Sizes 

## Component Colours of Light theme

* Background Colour of the Application - ![#ffffff](https://placehold.it/15/ffffff/000000?text=+) `#ffffff`
* Background Colour Message History -![#f5f4f6](https://placehold.it/15/f5f4f6/000000?text=+) `#f5f4f6`
* Chat bubbles Colour- 
    * Chat bubbles of SUSI- ![#fffff](https://placehold.it/15/ffffff/000000?text=+) `#ffffff`
    * Chat bubbles of User-  ![#e0e0e0](https://placehold.it/15/e0e0e0/000000?text=+) `#e0e0e0`
* Top Bar Colour-  ![#4285f4](https://placehold.it/15/0084ff/000000?text=+) `#4285f4`
* Buttons Colour- ![#4285f4](https://placehold.it/15/0084ff/000000?text=+) `#4285f4`
* Colour of search result- ![#ff5e00](https://placehold.it/15/ff5e00/000000?text=+) `#ff5e00`

* Toggle Colour- 
    * thumbOnColor- ![#5ab1fc](https://placehold.it/15/5ab1fc/000000?text=+) `#5ab1fc`
    * trackOnColor- ![#4285f4](https://placehold.it/15/0084ff/000000?text=+) `#4285f4`

* User Feedback Colour-
    * Thumbs Up Colour-
         **Voted**- ![#1685e5](https://placehold.it/15/1685e5/000000?text=+) `#1685e5`
         **Unvoted**- ![#90a4ae](https://placehold.it/15/90a4ae/000000?text=+) `#90a4ae` 

## Fonts

* Font Type of Chat Message-  "Product Sans", sans-serif
* Font Type of Message Composer-  "Product Sans", sans-serif
* Chat Message font size :14px
* Chat Composer font size : 16px
* Font Colour of Chat Message- ![#001d38](https://placehold.it/15/001d38/000000?text=+) `#001d38`
* Font Colour of Message Composer- ![#001d38](https://placehold.it/15/001d38/000000?text=+) `#001d38`
