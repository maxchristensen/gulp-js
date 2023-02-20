# GulpJS
### Your best friend for **creating local fullstack sites easy.**

### Steps
1. Ensure that you change your directory to the root folder you are trying to activate gulp in
2. Initialise Node Package Manager (NPM) by type *npm init*
3. Open up the Gulpfile.js in the repo, and check what **dependencies** are listed. Dependencies are exactly what the name would suggest, they are a number of applications that the website requires in order for it to be developed smoothly.
4. Install all of the dependencies listed by going *npm i* followed by your npm name (e.g. gulp-jshint)
5. Once all NPMs have successfully been installed, we need to make one minor change to the Gulpfile.js. Open up the Gulpfile.js, and look for the scripts section of the file, and add the following line after the existing test script: *"gulp": "gulp"*. We add this just as a safety precaution if gulp doesnt work when we try to boot it up.
6. All that is left to do is simply type *gulp* or *npm run gulp* to get gulp started. If successful, you will se that it says a range of things have started running and a link, somewhere alongs the lines of **localhost:** simply command/control + click on the link to open it up inside of the browser and access your new locally hosted server!
7. To stop gulp, simply press control + c inside of the terminal to stop the server from running.
