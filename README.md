Meteor

Meteor is an open-source, full-stack JavaScript framework that makes it easy to write top-quality web apps in a fraction of the time. What once took weeks, even with the best tools, now takes hours with Meteor.

It has a very different philosophy compared to other existing JavaScript frameworks like AngularJS, BackboneJS, etc. Normally, when we work with backbone or angular, the client side(Angular or Backbone) talks with a REST backend. We can write REST backend in any technology like Java, NodeJS, PHP,etc.

In Meteor, DDP(Distributed Data Protocol) protocol is used to transfer the data between client and server. DDP is a standard way to solve the biggest problem facing client-side JavaScript developers: querying a server-side database, sending the results down to the client, and then pushing changes to the client whenever anything changes in the database.

The server side of a Meteor application works on top of Node and MongoDB. We write both the client and server side of the application using Meteor APIs.


A library of packages: pre-written, self-contained modules that you might need in your app.
There are about a dozen core Meteor packages that most any app will use (for example webapp, which handles incoming HTTP connections, and templating, which lets you make HTML templates that automatically update live as data changes). Then there are optional packages like email, which lets your app send emails, or the Meteor Accounts series (account-password, accounts-facebook, accounts-ui, and others) which provide a full-featured user account system that you can drop right into your app. And beyond these "official" packages, there are hundreds of community-written packages in Atmosphere, one of which might do just what you need.


A command-line tool called meteor.
meteor is a build tool analogous to make, rake, or the non-visual parts of Visual Studio. It gathers up all of the source files and assets in your application, carries out any necessary build steps (such as compiling CoffeeScript, minifying CSS, building npm modules, or generating source maps), fetches the packages used by your app, and outputs a standalone, ready-to-run application bundle. In development mode it can do all of this interactively, so that whenever you change a file you immediately see the changes in your browser. It's super easy to use out of the box, but it's also extensible: you can add support for new languages and compilers by adding build plugin packages to your app.

The key idea in the Meteor package system is that everything should work identically in the browser and on the server (wherever it makes sense, of course: browsers can't send email and servers can't capture mouse events).

Structuring your application

A Meteor application is a mix of JavaScript that runs inside a client web browser, JavaScript that runs on the Meteor server inside a Node.js container, and all the supporting HTML fragments, CSS rules, and static assets. Meteor automates the packaging and transmission of these different components. And, it is quite flexible about how you choose to structure those components in your file tree.

HTML files in a Meteor application are treated quite a bit differently from a server-side framework. Meteor scans all the HTML files in your directory for three top-level elements: <head>, <body>, and <template>. The head and body sections are separately concatenated into a single head and body, which are transmitted to the client on initial page load.

Template sections, on the other hand, are converted into JavaScript functions, available under the Template namespace. It's a really convenient way to ship HTML templates to the client. 

In Meteor, the client and server share the same database API. But while code running on the server has direct access to the database, code running on the client does not. This distinction is the basis for Meteor's data security model.

METEOR IN A NUTSHELL

All JavaScript.
Applications which act in realtime.
Powerful data synchronization. Your client code can directly access database.
Realtime code update. You can update code even when users are online. As soon as you distribute the new code, updates are available on each browser frame with the app opened. 
One stop application bundle. You can compile the entire code with a single command.
Code Security. You can make the sensitive code run in a privileged environment. 
By default, Meteor uses the Handlebars templating library.
Meteor runs on top of node.js and uses MongoDb database.When you install the meteor package, it also downloads the latest version of the MongoDB. 
