#Uber Dev env
clone all of your projects into the projects directory and run vagrant up to run our standard env.

You will need access to our cookbook and will require a key. Contact Matthias at masa7872@colorado.edu to get one.

Once you are developing you will need to run vagrant ssh to actually build and run the code. However the code directory 
will be synced with the one on your actual file system. Meaning that any changes there will show up in the server. If you 
use a program like liver load for web development it will monitor for changes and automatically reload the application. 

## Warning
Warning if you are using a windows machine for development line endings are encoded differently and can lead to project corruption. Several IDE's will correct for this like WebStorm but only AFTER CONFIGURATION. Note this may not be a problem but if you are seeing weird issues this could be one. 
