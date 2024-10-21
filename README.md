# <h1 align="center">Weather App</h1>

<br>

Building a Weather app with JavaScript is an excellent project for beginners. It helps to understand the core basics of the DOM and teaches how to use fetch API, to call and get data from a third-party service.<br>

This is a simple javascript project made with the help of HTML, CSS, and OpenWeather API. We used weather API to fetch data and display it according to the city entered in the search bar.


to run the app:

1. Clone the Repository
You cloned the repository from GitHub to your local machine. Initially, there was a mistake in the URL, but after fixing it, you successfully cloned it.


###git clone https://github.com/yashchaudhary05/weather_app.git

This downloaded the project to the folder weather-app in your working directory.

2. Navigate to the Project Directory
After cloning, you navigated to the project directory:


###cd weather_app

3. Install Dependencies
You ran npm install to install all the required dependencies for the project. This installs the packages listed in the package.json file, including Gulp.

###npm install

This step also raised a few warnings about deprecated packages, but it didn't block the installation.

4. List Available Gulp Tasks
You checked the available Gulp tasks in the project by running:

###gulp --tasks

This showed that the Gulp tasks available were:

css
watch
sync


5. Run the Gulp Sync Task
You ran the sync task, which is the task responsible for serving the project with Browsersync:


###gulp sync

This started a local server and opened the project in your browser at:

Local URL: http://localhost:3000
External URL: http://172.25.16.1:3000
Browsersync is also watching for any file changes, and it will auto-reload the browser if you modify any files.

6. Access the Project in the Browser
You opened the browser and accessed the project at http://localhost:3000.
