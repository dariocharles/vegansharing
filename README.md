# <div align="center">Flask Framework</div>

[Live Project Here](https://vegan-sharing-app.herokuapp.com/)

In this project, I used Flask and MongoDB to build a website that people can share their vegan recipes. The website contains login, logout and CRUD functionality. 

# Table of contents

1. [Goals](#goals)
2. [Extra Features](#extra) 
3. [Technologies](#technology)
4. [Deployment](#deployment)
5. [Credits](#credits)

## Goals <a name="goals"></a>

### User Goals

To find and share vegan recipes with a community.

### Website Goals

 To build a community and reach a point where big enough to monetize off afiliate marketing and ad revenue. 
 
### Developer Goals

To store and access data from MongoDB. To use Flask in order to build the website functionality.

In this web application I showcased my abilities in the following:

- Flask Framework
- MongoDB
- Jinja syntax
- Python3
- CSS3
- HTML5

## Extra Features <a name="extra"></a>

If I were to continue working on this project I would add the following:

- Upload and Display Images for each recipe
- API to generate recipes
- abilitiy for users to comment on recipes
- forum to discuss recipes and cooking
- Validation on forms
- Contact Page

## Technologies Used <a name="technologies"></a>

### Languages Used

- HTML5
- CSS3
- Python3
- Flask
- MongoDB

### Frameworks, Libraries & Programs Used

1. [Git](https://git-scm.com/)

2. [GitHub](https://github.com/)

3. [Flask](https://flask.palletsprojects.com/en/2.0.x/)

4. [Heroku](heroku.com)

5. [Font Awesome](https://fontawesome.com/)


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
- [Bootstrap](https://getbootstrap.com/)

### Acknowledgements

- My teacher at Canadian Business College for assisting and encouraging me to build this application. 
- The Code Institute for providing course material to assist in learning how to implement the contents of this website
