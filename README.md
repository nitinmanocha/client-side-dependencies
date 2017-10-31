# client-side-dependencies

Dependencies means the libraries that are required to make the webpage work. It helps in dealing with complex projects . It also allows us to keep track and update libraries faster and easier. It is also called package because it is a collection of libraries.

Dependencies can be managed by using dependency manager or package manager.
NPM
NPM is a package manager for the javascript programming language. It is the default package manager for the JavaScript runtime environment . It consists of a command line client. npm can manage local dependencies of a particular project.
with the help of it we can Find packages of code from thousands of people and reuse them in new ways.it can reduce our programming work.
2. BOWER
Bower is a package manager for web applications. It uses bower.json as the configuration files. This file isgenerally in a root directory of the application.
Bower dependencies are .js, .css and other files required for application like jQuery, bootstrap etc. These dependencies are copied into a directory configured into .bowerrc file with a directory attribute at app/bower_components. It allows us to update dependencies time to time.
3.YARN
Yarn is a new package manager that replaces the existing workflow for the npm package managers. It is Compatibility with both the npm and bower workflows. It uses the same package.json file, and saves dependencies to the node_modules. new versions of yarn will be released and to update to the latest version time to time.
The 3 steps of installation process of Yarn are:-
Resolution: Yarn starts resolving dependencies by making requests to the registry and looking up each dependency.
Fetching: Yarn looks in a global cache directory to see if the package needed has already been downloaded.
Linking:Yarn links everything together by copying all the files needed from the global cache into the local node_modules directory.
