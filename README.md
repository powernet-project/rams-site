# Ram's personal site hosted via Stanford's AFS

This site is hooked up to CircleCI for deployment.
Any commit/push to master will trigger a build and a subsequent deployment to AFS.  
The whole project directory will be overwritten on the server - please be cognizant of this when
making changes. Preferably, make a PR!

#### Cloning the source code
```
git clone https://github.com/powernet-project/rams-site.git
cd rams-site
git checkout master
```

#### Setup
None at this time. This project is a simple and trivial web site. There are basically no dependencies, databases or anything else to worry about at this time.

To run the project simply open the index page. Beware of browser restrictions when serving sites from the local FS.

However, if you absolutely want to run this served from localhost, assuming you are on OSX with python 3, just navigate to the folder and run:

```
python -m http.server
```

Then navigate to localhost:8000 on your browser of choice.

Everything else should be pretty intuitive and Google-able. 
