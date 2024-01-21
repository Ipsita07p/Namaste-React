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

It can also be called `dead code elimination`





