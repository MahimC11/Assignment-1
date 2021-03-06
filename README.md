# assignment-1
This is a website that will be used in order to host my portfolio on.

## UX
this website will be used by people, potentially employers, who will be interested in having a look at what will be hosted on my portfoilio

## Features

### All pages
- Dropdown navbar titled Menu
- Media links in the footer that change colour when hovered over

### index.html (homepage)
- Slideshow that is currently filled with placeholder images, these will eventually be replaced with projects that i have completed or am currently working on

### about.html
- N/A

### contact.html
- A form to submit any messages or requests to me

### Upcoming Features
- Darkmode, This feature is functional however isn't needed as the current colour scheme is quite dark anyway. This feature could be changed by either changing the default colour scheme to be lighter or by inverting the effect of the darkmode button by making the colour scheme lighter after using it.

## Used Technologies
- [**HTML5**] This has been used to develop the basic elements on the website.
-[**CSS3**] CSS3 has been used in order to style the elements held on the website.
-[**Bootstrap**] Bootstrap has been used in order ot provide a responsive grid system as well as some pre-made styles.
-[**JavaScript**] JavaScript has been used in order to add some functionality onto the website.
-[**Git**] Git has been used in order to implement a version ccontrol system that can add and commit changes on the project before pushing them onto GitHub
-[**GitHub**] GitHub is used as  aremote repository that will hold and changes that are pushed from my local repository. I will aslo use GitHub Pages to deploy the website into a live environment.

## Testing

### All pages
- Media Links in the footer have no links assigned to them yet.
 
- Dark mode button would need some changees made to it in order to have a meaningful function.

### index.html
- Slideshow works correctly, the buttons on the slideshow also work properly
- Navbar works correctly.

### contact.html
- The form on contact.html properly sends me forms to my formspree account and email.

### Other testing notes
- Everything works fine on mobile devices, however when loading the mobile view on a desktop in the developer console the contact.html page is sized incorrectly, this problem is easily fixed when changing back and forth from the contact page. No functionality issue is observed from this.
- When loaded from GitHub Pages the images wouldn't load, this problem doesn't occur when the website is loaded locally.

## Deployment

I have decided to use Github Pages to host my website. To deploy my website to GitHub pages, I used the following steps:

1. Loaded the terminal window in Visual Studio Code.
2. Initialised Git using the `git init` command.
3. Added all files to the Staging area (Git) using the `git add .` command.
4. Committed the files to Git using the `git commit -m "Initial commit"` command.
5. Created a new repository in GitHub titles 'Assignment-1'.
6. Copied the below code from GitHub into the terminal window in Visual Studio Code:

    ```git remote add origin https://github.com/MahimC11/Assignment-1```

    ```git push -u origin master```

7. Entered my GitHub username and password to push the files from Git to GitHub.
8. Went into 'Settings' on my repository page in GitHub.
9. Selected the 'master branch' option under the 'GitHub Pages' section.
10. Ran several regular commits throughout my project.

### GitHub Repository link
https://github.com/MahimC11/Assignment-1

### Running Code Locally

The code for this website can be run locally by following the steps below:


- Go to [my GitHub repository](https://github.com/MahimC11/Assignment-1).
- Click on 'Clone or download'.
- Click on 'Download ZIP'.
- Once dowloaded, extract the zip file's contents and run my website locally.

## Credits

- Coming Soon image was made by me
- Slideshow on index.html was from https://www.w3schools.com/bootstrap/bootstrap_carousel.asp
- Form API on contact.html is from Formspree.io
