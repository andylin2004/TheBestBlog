# TheBestBlog

RAIDED BY ANDY LIN AND MARK ZHU BUT WE GOTTA GO FAST
Gotta Go Fast - Andy Lin, Mark Zhu
SoftDev
K20 - applying own css on someone's webpage notes
2021-11-24
time spent: 1.5

notes

inputs are editable by using input[type=whatevertypeyouwant] and customizing the inside
you can use css to force the whole website to be comics sans because i can
you can customize the behavior of when a cursor is over a limk with a:hover and customizing what happens to the cursor
font size can be changed on form elements
you can remove borders from form buttons to make it less ugly. dont do it on text inputs, as people will end up having issues detecting where the form inputs are
https://coolors.co/ is a great website to get color palettes

TheBestBlog by Team The Best Cameron
<br>
Cameron Nelson - Python/SQLite3/Backend
Alif Abdullah - Python/SQLite3/Backend
Kevin Cao - HTML/Jinja/CSS Frontend
Jonathan Wu - HTML/Jinja/CSS Frontend

## About
* TheBestBlog is a blog hosting site. 

* On the homepage, all users are greeted to TheBestBlog, with logged in users being addressed by their username. 		
	* Users who are not logged in may register an account and/or login. Logged in users have the ability to create a new blog and logout. 
	* All users, logged in or not, are able to view all blogs stored in the site's databases, or can view a random blog. Only logged in users can create new blogs and check out their own blogs. 

* Clicking My Blogs or All Blogs on the home page brings you to a page with a list of blogs. 
	* Users may update their blogs with a new entry on the My Blogs page.
	* They may also click on one of the blogs in their My Blogs page and edit each entry of their blog or update the blog with a new entry.
	* On the All Blogs page, users can view every blog posted on the site. 
		* Viewers who are not logged in or viewers who did not make the blog can only view the blog's name and contents.
		* Viewers who have made the blog have the option to edit and update their blog.

* Clicking Random Blog brings users directly to a random blog, where the rules mentioned regarding viewing, editing, and updating blogs still apply.

## Install Instructions:

Run the following commands in a terminal shell with git and python installed:

`git clone git@github.com:cnelson20/TheBestBlog.git`

`cd TheBestBlog/app/`

`python3 -m venv ~/blogenv`

Wait until that process finishes, then run:

`source ~/blogenv/bin/activate `

If you use windows, you may have to run source `~/blogenv/scripts/activate` instead

If that works, your terminal should appear something like this: <br>
`(blogenv) ~/TheBestBlog/app/`

If that's correct, run <br>
`pip install -r ../requirements.txt`

Wait for that to complete, and then

`python3 app.py` and the webserver should start up and start serving pages.
