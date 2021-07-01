
Planning/Organizing/ and Setting Up. 


Modal for delete button - https://getbootstrap.com/docs/4.0/components/modal/


https://www.youtube.com/watch?v=6WruncSoCdI - for upload file

Code
Register Form - https://bootsnipp.com/snippets/or3WG



https://getbootstrap.com/docs/5.0/components/card/ - for the cards for recipes

Er diagram
Site Map
WireFrame

-database frontend backend
-CRUD

Home page and add form wireframe


Planning Day:
o	Finalize application idea and have a clear user and site owner goal.
o	List of features to include.
o	Wireframe
o	Sitemap
o	ER Diagram



Goals
-External user’s goal:
Find and share recipes, comments so are able to see reviews of the recipe
Site owner's goal:
Promote a brand of cooking tools./Build a community (when big enough can monetize)


(Potential features to include:
Create a web application that allows users to store and easily access cooking recipes. Recipes would include fields such as ingredients, preparation steps, required tools, cuisine, etc.
Create the backend code and frontend form(s) to allow users to add new recipes to the site, edit them and delete them.
Create the backend and frontend functionality for users to locate recipes based on the recipe's fields. You may choose to create a full search functionality, or just a directory of recipes.
Provide results in a manner that is visually appealing and user friendly.
Advanced potential feature (nice-to-have)
Build upon the required tools field to promote your brand of kitchen tools (e.g. oven, pressure cooker, etc…).
Create a dashboard to provide some statistics about all the recipes.
)
README -
Main Technologies
HTML, CSS, JavaScript, Python+Flask, MongoDB
Additional libraries and external APIs
Mandatory Requirements
A project violating any of these requirements will FAIL
1.	Data handling: Build a MongoDB-backed Flask project for a web application that allows users to store and manipulate data records about a particular domain. If you are considering using a different database, please discuss that with your mentor first and inform Student Care.
2.	Database structure: Put some effort into designing a database structure well-suited for your domain. Make sure to put some thought into the nesting relationships between records of different entities.
3.	User functionality: Create functionality for users to create, locate, display, edit and delete records (CRUD functionality).
4.	Use of technologies: Use HTML and custom CSS for the website's front-end.
5.	Structure: Incorporate a main navigation menu and structured layout (you might want to use Materialize or Bootstrap to accomplish this).
6.	Documentation: Write a README.md file for your project that explains what the project does and the value that it provides to its users.
7.	Version control: Use Git & GitHub for version control.
8.	Attribution: Maintain clear separation between code written by you and code from external sources (e.g. libraries or tutorials). Attribute any code from external sources to its source via comments above the code and (for larger dependencies) in the README.
9.	Deployment: Deploy the final version of your code to a hosting platform such as Heroku.
10.	Make sure to not include any passwords or secret keys in the project repository.






Features
-CRUD - Create functionality for users to create, locate, display, edit and delete records (CRUD functionality). - Are you sure you want to delete this - defensive

-login/logout accounts editing only what posted as well as admin editing
-Comments
-Make account

Extra
-API
-search functionality?
-page that just has the recipes the user contributed – user profile
-dashboard with statistic of each recipe
-forum

Name
Time
Date submitted
Who submitted
Ingredients
Directions
Nutritional Facts





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