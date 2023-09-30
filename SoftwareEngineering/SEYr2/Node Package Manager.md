A tool that is automatically installed when you install [[Node.js]]
- used to install shared node packages to enhance reusability

When we use 3rd-party packages it means our code depends on it.

We need to keep track of dependencies, so that when we get to package out code and ship it, we know what other packages need to exist in order to run out code

In preperation for installing 3rd party packages we initialize our program by creating a JSON file with the name package.json to include information about the package that we are creating.

to do so we run ==init==. It will ask to input the values to be stored in package.json. we can leave it with the default values by pressing enter for all the questions then yes for the last one. or to avoid the questions write --yes after init

```node
//to initialize:
//with defaults:
npm init --yes
//custom:
npm init

//to install:
npm install packagename

//to uninstall:
npm uninstall packagename
```
