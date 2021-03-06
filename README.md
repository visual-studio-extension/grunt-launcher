### GruntLauncher

[![Build status](https://ci.appveyor.com/api/projects/status/objiqfvmt0wlxed4/branch/master?svg=true)](https://ci.appveyor.com/project/Bjornej/gruntlauncher/branch/master)

Originally a plugin made to launch grunt tasks from inside Visual studio by right-clicking your gruntfile in the solution explorer it has now been extended with new functionality:

- Launch grunt tasks from the solution solution explorer. When  right clicking on a gruntfile you will see a new submenu listing all your options 

![grunt](http://bjornej.github.io/images/grunt.png)

- Execute bower updates when right clicking on the bower folder or on a plugin folder (thanks to Mads Kristensen for this feature) 

![bowerall](http://bjornej.github.io/images/bowerall.png)
![bower](http://bjornej.github.io/images/bower.png)

- Launch gulp tasks by right clicking on your gulpfile

![gulp](http://bjornej.github.io/images/gulp.png)

#### Attention

To work well this plugin needs a recent version of node.js installed on yout system due to a bug where output is not correclty redirected. If you don't see any output try to update node.js.

Node.js and also any tools invoked by grunt or gulp must be available in the system PATH variable. If you have to modify it because a tool is not found you'll have to restart Visual Studio for the change to be seen.
