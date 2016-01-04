# CodeFresh beautify example plugin

The purpose of this example is to show how to write simple Orion plugin, extend it and work with it
In this example we have developed very simple JS beautify plugin that will add menu item ('Beautify JS' under the 'Tools' drop down menu) that cab be executed on any .js file (visible when a JS file is opened).
This implementation is also using Orion settings mechanism to extend the user experience by letting him select how to use the beautify logic.



## Code It

There are 2 options of how to run and try out this plugin.
- Go to [Codefresh Labs](http://www.codefresh.io/labs) and click on the Orion plug-in example
- Clone the repo locally and host it on any other server


## Using [Codefresh Labs](http://www.codefresh.io/labs)
- View or make any change to the plug-in implementation in the index.html file
- Click on the run button to host your plug-in in the server ![Run](img/run.png)
- Open the URL to the plug-in (you need the URL to install the plug-in) ![Open URL](img/openurl.png)
- In the opened URL you can either 
--Click on the 'install in caodefresh' to install the plug-in on the codefresh. The link will take you tot he codeffresh ide setting. install the plug-in then refresh your IDE
--Copy the URL and open any Orion setting page and install the plug-in using the copied URL

## Install Your plugin locally
Once you downloaded the git repository, open terminal and run the following:
npm install
npm start

if you run it locally your plug-in URL is as follow:

[http://localhost:9000/](http://localhost:9000/)


In order to install it in Orion IDE go tot he setting page in the Orion IDE.
If you dont have any available Orion IDE you can open an account at Orion Hub

[http://orionhub.org](http://orionhub.org)

In the setting page, go to plugins category, click the install button, put the plug-in URL and approve it.

## Test It

You plugin is now installed, get into the editor, open JS file, add some content.
Once you would like to beautify it, just click Tools>Beautify and it should see that the code is getting arranged.

## Update plugin

If you are only updating the plugin logic, all you have to do is refresh your page and the changes will get into effect.
If you would like to add/remove/update Orion extension points, you will need to get into the plugins page and click the refresh button on our specific plugin.

## You can see plugin hosted on Heroku 
https://orionplugin.herokuapp.com/

#
