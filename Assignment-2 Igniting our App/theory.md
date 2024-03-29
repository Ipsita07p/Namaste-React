# What is `NPM`?

NPM is a tool for package mangerment thus manages all packages for Node.js. It is a node package manager but doesn't have any full form.
npm alternative is yarn.

# What is `Parcel/Webpack`? Why do we need it?

Parcel/ Webpack are open-source JavaScript bundlers which as the name suggests bundles the code in files together to make it production ready. 

It's basically web application bundler used for development and productions purposes or power our application with different type functionalities and features.

Parcel can be more preferrable in comparison to webpack because of it's speed and easy-to-use.

We need it because of it's core features which are listed below:
*Development: Dev build, local server, hot reloading, caching, hosting at HTTPS.

*Production : Minification, tree shaking (remove unused code), file compression, image optimization, content hashing, differential bundling (gives different versions for different browsers suppoting older versions).

*Code splitting
*Diagnostics

# What is `.parcel-cache`?

.parcel-cache is a directory created by Parcel bundler which stores information about a project when Parcel builds it. 

By default, the cache is stored in the .parcel-cache folder inside a project. It is recommended to add this folder to the .gitignore.

# What is `npx`?

npx checks whether <command> exists in local project and executes it. 
It gives an advantage of executing a package which wasn't previously installed.

It comes with the npm, when you installed npm above 5.2.0 version then automatically npx will installed.

# What is difference between `dependencies` vs `devDependencies`?

`Dependencies` are libraries/packages that a projects needfs to function effectively. These are needed for both development and production phases of project.

While `devDependencies` are packages required during development phase of an project thus cannot be included in production phase.

# What is `Tree Shaking`?

Tree shaking can be seen in production builds where Parcel analyses the imports and exports of each module, and removes everything(basically the code) that isn't used while production. 

It can also be called `dead code elimination`.

# What is `Hot Module Replacement`?

Hot Module Replacement updates modules in the browser at runtime without needing a full page refresh ultimately improving development. 

In this case, application state can be retained as there are small changes in code.

# List down your favourite 6 superpowers of Parcel and describe any 3 of them in your own words.

1. Minification: 
    Parcel includes minifiers for JavaScript, CSS, HTML, and SVG out of the box. Minification reduces the file size of your output bundles by removing whitespace, renaming variables to shorter names, and many other optimizations.

2. Tree shaking: 
    Tree shaking can be seen in production builds where Parcel analyses the imports and exports of each module, and removes everything(basically the code) that isn't used while production.

3. Caching: 
    Parcel caches everything it builds to disk. If you restart the dev server, Parcel will only rebuild files that have changed since the last time it ran. Parcel automatically tracks all of the files, configuration, plugins, and dev dependencies that are involved in your build.

    By default, the cache is stored in the `.parcel-cache` folder inside project.

4. Hot reloading

5. Diagnostics

6. Differential bundling

# What is `.gitignore`? What should we add and not add into it?

`.gitignore`file is a simple text file that tells Git which files/directories to ignore from tracking. 
By this we can keep our repository focused on essential files and avoid cluttering with unnecessary files.

`In React project,` 
`.gitignore file would include,`
* node_modules
* build
* security key files and API Keys

`.gitignore shouldn't include,`
* files part of project history
* files necessary for building/running project

# What is the difference between `package.json` and `package-lock.json`?

`package.json`:
* This configuration file is mandatory for every project that lists the dependencies.
* It is human -readable and -editable file used to specify desired version of dependencies.
* It contains basic information about the project.
* Application name/version/scripts

`package-lock.json`:
* This version locking file is machine-generated for those operations where npm modifies either the node_module tree or package-json.
* It is generated after an npm install.
* It allows future devs & automated systems to download the same dependencies as the project.
* It records the same version of the installed packages which allows to reinstall them.

# Why should I not modify `package-lock.json`?

The `package-lock.json` file is not intended to be manually edited. It is a generated file that tracks the entire dependency tree and the exact version of each dependency.

Modifying it would cause dependencies issues in the production environment as it's automatically handled by NPM.

# What is `node_modules` ? Is it a good idea to push that on git?

node_modules folder like a cache for the external modules that our project depends upon. When npm installs them, they are downloaded from the web and copied into the node_modules folder and Nodejs is trained to look for them there when you import them (without a specific path). 

`node_modules can't be pushed in git` because it contains lots of files (more than 100 MB), it will cost you memory space.

# What is the `dist` folder?

The dist folder(short for distribution folder) is a directory that stores the compiled or minified version of an application. 

It is used to deploy an application to a production environment. This is because the compiled and minified code is smaller and faster than the source code, which can improve the performance of the application.

# What is `browserslist`?

`browserslist` is a tool that allows specifying which browsers should be supported in your frontend app by specifying "queries" in a config file. It's used by frameworks/libraries such as React, Angular and Vue, but it's not limited to them.












