steps to get the test app running:
==========

#### the first time, you have to do steps 1-3 (after the first setup, you can start off with step 3)

1. get the files on your local machine:
	* checkout master branch:
		* type ```git branch``` in your terminal to make sure you are on **master** branch
		* if not, save/commit/stash/move your changes for now, then type in: ```git checkout master```
		* ```git fetch``` will get you the latest and greatest from the master branch
			
			
			
			
2.  install meteor: <https://www.meteor.com/install>
	* basically just go to your folder containing the app files and copy and paste:
	```curl https://install.meteor.com/ | sh```
	* click “allow” incoming connections when prompted by pop up
3. run app:
	* make sure your are in the correct folder: **social-travel-itinerary/app**
	* type in: ```meteor``` on terminal
		* (it will load some stuff, then eventually tell you it is running and to go on to: <http://localhost:3000/>)
	* you can now view the current version of the site and log on to FB!
		* remember, it's currently viewble at: <http://localhost:3000/> on your browser
		* as of now, you still need to enter the facebook config info the first time you try to log in on your computer (**app id** + **app secret**: <https://docs.google.com/document/d/1gQ6zDga3NKw_JDqI27eQV4rt_qvwOtfhaNCY1nnj2e4/edit> -> meteor-based app info)
4. Play around with meteor! Start with the meteor tutorial: <https://www.meteor.com/tutorials/blaze/creating-an-app>
