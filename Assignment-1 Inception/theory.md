# What is Emmet?
Emmet is a powerful tool for writing HTML and CSS Code using shortcuts which later expands
into line of codes. It’s usually preinstalled in VS Code

# Difference between a Library and Framework?
Library- 
    Collection of reusable functions.

    Code controls when to call library giving higher degree of control.

    Provides flexibility.

    Ex, React.js is JS library
    
Framework-
	Code that dictated project architecture.

	Framework control when to call libraries giving no control.

	Provides least flexibility due to enfored structure.

	Ex, AngularJs is JS framework

# What is CDN? Why do we use it?

cdn, i.e., Content Delivery Network is group of servers that store copies of data so that
servers can fulfill data requests based on which servers are closest to end-users.

It is widely used for delivering stylesheets and JS files of libraries.
It impoves site performance, reduces server load, and server cost by handling heavy traffics.

# Why is React known as React?

React is called React because of its core feature which is to respond or “react” to data changes/ user interactions and react to state changes resulting in instant updating of the components of the app composing the user interface.

# What is crossorigin in script tag?

cross-origin attribute is crucial to load resources of other servers, CORS (cross-origin resource sharing which is an HTTP header-based mechanism) manage cross-origin requests and defines a way for the browser and the server (where the resources are) to interact to determine if it is safe to allow cross-origin requests, also allow the server to decide who can access it's assets.

# What is diference between React and ReactDOM

React library is responsible for creating components while ReactDOM library renders user interface ready for user interaction.

# What is difference between react.development.js and react.production.js files via CDN?

react.development.js  is development mode that allows the debugging environment through react developer tools and detailed error messages features. 

react.production.js is Production mode that allows the compression and minification of js code and other resources which reduces bundle size resulting in efficient performance.

# What is async and defer?

These are attributes in the script tag.

In case of using async attribute : HTML parsing is ongoing in parallel with the file loading but once the file is loaded, HTML parsing is paused till the js code of the file is fully executed.

But in case of using defer attribute : HTML parsing is ongoing in parallel with the file loading and once HTML parsing is done, the js code of the file will start to be executed.