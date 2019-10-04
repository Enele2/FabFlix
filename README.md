# FabFlix
The project comes from my graduate course CS122B: Projects in Databases and Web Applications.

FabFlix is a Movie Sales Website, which can provide visitors basic functions including fuzzy search and prefix search for all the movie, directors, actors, categories, etc. In addition, visitors can add movies into their shopping cart to pay for that.

For the front-end, we built a web application and an Android app to let users to exprience this product(Javascript, Ajax, jQuery, HTML5, CSS).

For the back-end, we implemented a database to store all the data by using MySQL, furthermore, we parse a vast amount of data into the database using Java.

We deployed the whole product mainly on AWS EC2 and Tomcat as our server to provide services for the request. We tried many ways to reduce the latency and improve the efficiency, tested it by JmMter. To list them: procedure, use master-slave cluster method, connection pooling, cookies, etc. 
