# Template for WCS Explorations x Infrastructure frontend workshop

This workshop requires basic working knowledge of the Git workflow, specifically forking, cloning, making changes, and pushing. For more information on the Git workflow and practice resources, check out the Illinois WCS Explorations website: http://wcs.illinois.edu/explorations/index.html/

## How to use
1. Make a fork of this repository by clicking the button in the top right corner. This makes a copy of the repository that is independent from the original and allows you to make modifications as you please.
2. Go to the settings tab for your fork. At the top, there is a box to rename the repository. If you do not already have a personal site and you'd like to use this repo as your personal site, change the repo name to `<YOUR USERNAME>.github.io`; if you do, you don't need to change the repo name (instead, it will deploy to `YOURDOMAIN/fabulous-frontend`; if you want a different name for the URL, change the repo name accordingly). 
3. Clone to your local machine using `git clone <REPO URL>` where `<REPO URL>` is the URL repo obtained by clicking the green dropdown on the top right corner of your screen.
4. Modify index.html, index.js, and styles.css as desired
5. Test your local changes by opening index.html using your preferred browser. You can do this by using your machine's file explorer / finder or typing `index.html` into your terminal

## How to modify
This repository uses Bootstrap UI to build the frontend in `index.html`. Documentation on how to use Bootstrap and other UI elements you can use can be found on their website: https://getbootstrap.com/docs/5.0/getting-started/introduction/. Interactive componetns or animation can be made in `index.js`.

The document is currently styled using the WCS style guide. If you would like to change the colors and fonts, modify `styles.css`. 

## Publishing your page to the web
1. Push all of your local changes to the remote server. First, run `git add .` to track changes. Then, run `git commit -m "<INERT DESCRIPTIVE COMMIT MESSAGE>"` to bundle your changes into a commit with a descriptive label. Finally, run `git push` to push your changes to the remote. 
2. Go to the settings for your fork (on the GitHub website), then scroll to the middle of the page where it says "GitHub Pages." Change the `source` to the `main` branch using the dropdown and press the `save` button. This might already be enabled for you. Your site will be live at `<YOUR USERNAME>.github.io` or `YOURDOMAIN/fabulous-frontend` (depending on what you chose in step 2 of the above) soon!