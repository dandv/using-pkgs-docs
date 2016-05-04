# Global Installation

There are two ways to install npm packages: locally or globally. You choose which kind of installation to use based on how you want to use the package.

If you want to use it as a command line tool, something like the grunt CLI, then you want to install it globally. On the other hand, if you want to depend on the package from your own module using something like Node's require, then you want to install locally.

To download packages globally, you simply use the command `npm install -g <package>`, e.g.:

```
npm install -g jshint
```

If you get an EACCES error, you _should_ [fix your permissions](/getting-started/fixing-npm-permissions). You could also try using `sudo`, but this **should be avoided**:

```
sudo npm install -g jshint
```
