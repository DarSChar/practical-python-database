# <div align="center">Flask Framework</div>

[Live Project Here](https://mountain-flask-app.herokuapp.com/)

This project used the Flask Framework and Startbootstrap template to advertise a hotel in Canmore, AB. It is a three page website that uses a JSON file to retrieve data from to advertise each type of room available. 

![Screenshot](static/assets/img/evermore.png)

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

## Deployment <a name="deployment"></a>

### Heroku

The project was deployed to Herokku using the following steps...

1. Log in to Heroku.com and locate the Heroku apps
2. Create a new app and give it a unique name
3. Use the Heroku command line interface/Heroku Toolbelt. Install heroku using the command 'npm install -g heroku'
4. Use the command line to login into heroku. Use the command 'heroku login -i'
5. Go back to Heroku.com and click on open app to see the app is succesfully running.
6. Link local git repository to Heroku. First add all file to staging area using 'git add .' in the commant line and 'git commit -m "Deployment to Heroku"' to commit to github. On Heroku.com go to settings and copy Heroku Git URL. Back in the command line add another remote using the command 'git remote add heroku' and paste Heroku Git URL after. 
7. Create a requirements.txt file by typing 'pip3 freeze --local > requirements.txt' into the command line. Add this file to the staging area and commiting the change. Finally, use the command 'git push -u heroku master' to push to heroku. 
8. Create a Heroku Procfile by typying 'echo web: python run.py > Procfile' in the command line. Add this new file to the staging area, commit the change and git push. In heroku.com settings page and add hidden environment variables. Click on reveal config vars. Add IP 0.0.0.0, PORT 5000, SECRET_KEY secret_flash_key. These are variable from the document. Click the deploy tab and click connect to Github. Type in the repository name and click search to find the repository. Click connect. Click enable automatic deployment from master branch. Click Deploy Branch. Back in terminal type 'git remote rm-heroku' so only git is connected to the project and no longer heroku. Put in staging area and commit the changes to then push to github. 

## Credits <a name="credits"></a>

### Resources/References

- [The Code Institute](https://codeinstitute.net/)

### Images

- All images were taken from Google images.

### Acknowledgements

- My teacher at Canadian Business College for assisting and encouraging me to build this application. 
- The Code Institute for providing course material to assist in learning how to implement the contents of this website

