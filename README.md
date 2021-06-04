# <div align="center">Flask Framework</div>

[Live Project Here](https://dariocharles.github.io/js-milestone-project/)

This project used the Flask Framework and Startbootstrap template to advertise a hotel in Canmore, AB. It is a three page website that uses a JSON file to retrieve data from to advertise each type of room available. 

![Screenshot](static/assets/images/evermore.png)

# Table of contents

1. [Goals](#goals)
2. [User Experience](#UX)
3. [Testing](#testing)
4. [Deployment](#deployment)
5. [Credits](#credits)

## Goals <a name="goals"></a>

### User Goals

The user's goal is to learn more about the hotel and contact them for bookings. When they come to the website they will find that they can see which rooms are available. 

### Developer Goals

In this project, I implemented a Startbootstrap template, Python3 language for streamline code, and Flask framework to build the web application. I also deployed the project to Github and Heroku. 

In this web application I showcased my abilities in the following:

- Flask Framework
- Bootstrap Template
- Jinja syntax
- Python3
- CSS3
- HTML5

## User Experience UX <a name="UX"></a>

When the user comes to this website, they are greeted with an inviting feel and visually inticing experience. The imagry and design is sleek and relavent to the hotel giving the user a clear understanding of what they are seeking. When they submit the contact form they are provided feedback that their form is submitted and they will be replied to shortly. 

### Design

- Colour Scheme
  - This website is quite colourful and welcoming. The white background reflects the rich, clean mountain air that the hotel promotes. 
- Style
  - The style of the website is professional and information focused. 

## Technologies Used <a name="technologies"></a>

### Languages Used

- HTML5
- CSS3
- Python3

### Frameworks, Libraries & Programs Used

1. [Git](https://git-scm.com/)

2. [GitHub](https://github.com/)

3. [Flask](https://flask.palletsprojects.com/en/2.0.x/)

4. [Heroku](heroku.com)


## Testing <a name="testing"></a>

### Further Testing

- The Website was tested on Google Chrome, and Micrsoft Edge.
- The website was viewed on a Laptop device.
- Used Chrome Dev Tools to test responsiveness.
- Multiple games were played to ensure that the functions all worked with any interaction the user may use.
- I used [W3C Markup Validation](https://validator.w3.org/) to validate HTML
- I used [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) to validate CSS.
- I used [JSON Lint](jsonlint.com)) to validate the JSON file.


## Bugs

- The code had a bug that when the user double-clicked a card the function would see that as a match because the data attribute would match. This would keep the card flipped without matching with a new card. I created a function to resolve this issue so that clicking a second time would not trigger an event. That way it wasn't recognized as a match.
- A bug in the code was that when a user would click another card before the first card was fully turned over, the function had completed, then the second card would flip over but wouldn't recognize if the data attribute matched the first card or not. I created a function to resolve this issue so that the user couldn't click another card until the first function was completed.

## Deployment <a name="deployment"></a>

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page), locate the "Settings" button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page) just above the "Settings" button on the menu, locate the "Fork" button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the GitHub Repository
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.
   $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
7. Press Enter. Your local clone will be created.
   $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
   > Cloning into `CI-Clone`...
   > remote: Counting objects: 10, done.
   > remote: Compressing objects: 100% (8/8), done.
   > remove: Total 10 (delta 1), reused 10 (delta 1)
   > Unpacking objects: 100% (10/10), done.

## Credits <a name="credits"></a>

### Resources/References

- [The Code Institute](https://codeinstitute.net/)

### Images

- All images were taken from Google images.

### Acknowledgements

- My teacher at Canadian Business College for assisting and encouraging me to build this application. 
- The Code Institute for providing course material to assist in learning how to implement the contents of this website