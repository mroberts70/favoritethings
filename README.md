# favoritethings
Multi-Page website comprised of the video gallery, the flexbox image gallery, and the JavaScript slideshow

Live site: https://mroberts70.github.io/favoritethings/index.html

2022-04-07 - favoritethings Version 1 - Steps taken to reach current status:

First, we need all the files that are going to make up our website. I combined files from 3 previous projects into a single project named "favoritethings":
- I want to model the whole site off the style of the video gallery page, so I copied the entire contents of the video gallery project folder into my favoritethings folder (including the styles folder and images folder)
- I made a copy of the video gallery index.html file and named it videogallery.html
- I went into my imagegallery folder and made a copy of the index.html file and renamed it imagegallery.html. I put imagegallery.html in the root of my favoritethings folder
- I made a copy of my imagegallery main.css file and renamed it imagegallery.css. I put imagegallery.css in the styles folder of my favoritethings folder
- I went into my slideshow folder and made a copy of the index.html file and renamed it slideshow.html. I put slideshow.html in the root of my favoritethings folder
- I made a copy of my slideshow main.css file and renamed it slideshow.css. I put slideshow.css in the syles folder of my favoritethings folder
- I copied the images from my slideshow images folder and from my imagegallery images folder into the images folder of my favoritethings folder


Once all the files have been created/copied/gathered into the correct locations, we can do some clean up:
- I opened VS Code and used File/Open Folder... to open the favoritethings folder
- I opened the index.html page (which was just a copy of the videogallery page) and deleted everything between the section tags. This removes all the video code but leaves the return to top button Javascript
- I copied the JavaScript from the shapeup project that is used to display the current year in the footer and pasted it just above the footer in index.html
- I opened imagegallery.html and added a stylesheet link to imagegallery.css. I placed it after main.css
- I opened slideshow.html and added a stylesheet link to slideshow.css. I placed it after main.css
  

Finally, I added a navbar using bootstrap:
- First, I had to go to getbootstrap.com to get the css link for the head section, and the bundled js script link which goes just above the end body tag. These two pieces of code must be pasted into their respective locations in every html page in the favoritethings folder
- Next, you have the option of copying navbar code from either the getbootstrap.com website, or from w3schools: https://www.w3schools.com/bootstrap5/bootstrap_navbar.php
- I selected w3schools, and picked one of the options from the "colored nave bar" options, and copied and pasted the html code into the favoritethings index.html page after the closing header tag and before the opening main tag
- I then edited the code to include links to each of the other html pages in my favoritethings folder (videogallery.html, imagegallery.html, and slideshow.html)
- Once complete, I saved and tested the page and tested the navbar links. 
- After I verified that the navbar links all work correctly, I copied the nav code from index.html and copied it into the same location in each of the other html files in the same location (after the closing header tag). 
