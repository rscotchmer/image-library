# Image Library
## About
A work-in-progress tool that aims to help artists by pooling all of their visual references into one place.  The images are displayed in a gallery, and can be expanded to a larger size if needed.  The tool gets the images from the user, who can either drag and drop the image from its location on their system, or input the image's path.

## Set-Up
This project requires Electron, React, and a few other packages.  Clone this repo, and run `npm install` in the project directory to install all the necessary packages.  Afterwards, run `npm run electron-build` to have Electron build the necessary modules (such as sqlite3).

## To-Do
* Add a tagging system to filter images
* Implement lazy-loading to improve performance
* Investigate other ways to improve the performance -- the app tends to hang when loading a large number of images
* Add the ability to put in a URL to an image, which the tool can then use to download said image and add it to the gallery
