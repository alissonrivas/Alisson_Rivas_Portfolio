ALISSON RIVAS — DIGITAL PORTFOLIO
=================================

This is a static website made with HTML, CSS, and JavaScript. It does not need PHP,
MySQL, Node.js, or a build command to run as a portfolio.

FOLDER STRUCTURE
----------------
index.html                       Main website content
css/style.css                    Colors, layout, responsive design, and visual style
js/main.js                       Mobile navigation and scroll reveal animations
assets/profile-photo.webp        Your professional portrait
assets/project-previews/         Starter preview images for the three projects
.nojekyll                        Helps GitHub Pages publish static files as-is

OPEN THE WEBSITE
----------------
1. Extract the ZIP file.
2. Open the extracted folder in Visual Studio Code.
3. Open index.html in a browser, or use the Live Server extension in VS Code.

CHANGE THE PROJECT SCREENSHOTS (FROM THE CODE)
----------------------------------------------
There are no upload buttons on the website. To add your own screenshots:

1. Take a screenshot of each project website.
2. Copy the image files into: assets/project-previews/
3. Open index.html and find the section with the heading "Inside the projects".
4. Change the src of each image to the name of your screenshot. For example:

   <img src="assets/project-previews/furrylove-preview.svg" ...>

   can become:

   <img src="assets/project-previews/furrylove.png" ...>

Do the same for HUSH and ModaKids. Keep the spelling and upper/lowercase letters
of the filenames exactly the same. The screenshot files must remain inside the
project-previews folder when you publish the site.

CHANGE YOUR PROFILE PHOTO
-------------------------
The current photo is assets/profile-photo.webp. You can replace that file with
another image using the same filename, or change the image src in index.html.

UPDATE PROJECT LINKS
--------------------
- HUSH and ModaKids already point to the URLs included in your supplied HTML.
- The FurryLove project link is intentionally left as a placeholder because its
  published URL was not included. Search in index.html for "FurryLove project link"
  and replace the placeholder with your real website or repository URL.

GITHUB PROFILE
--------------
The GitHub profile link is set to https://github.com/alissonrivas based on the
GitHub Pages address used in the earlier setup. Please confirm that this is your
correct GitHub username before publishing. If your username is different, change
that URL in the Contact section of index.html.

PUBLISH WITH GITHUB PAGES
-------------------------
1. Upload the contents of this folder to the repository used for your portfolio.
2. Make sure index.html is in the repository's root folder.
3. In GitHub, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and the /(root) folder, then save.
6. Wait for GitHub Pages to publish the site; the URL will appear in Settings > Pages.

CUSTOMIZATION
-------------
All text is in index.html. Colors, typography, spacing, and responsive behavior are
in css/style.css. The interactive navigation and scroll animations are in js/main.js.
