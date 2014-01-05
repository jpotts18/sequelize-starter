Sequelize.js Starter Application
=================

<p align="center">
  <a href="http://sequelizejs.com">
    <img height="98" width="98" src="http://sequelizejs.com/images/logo.png"/>
  </a>
  <br/>
  <a href="http://gulpjs.com/">Visit Sequelize.js website!</a>
  <br/>
  <a href="http://sequelizejs.com/docs/latest/installation">Read the Documentations</a>
</p>

Sequelize's mission statement is the following:

>The Sequelize library provides easy access to MySQL, MariaDB, SQLite or PostgreSQL databases by mapping database entries to objects and vice versa. To put it in a nutshell, it's an ORM (Object-Relational-Mapper). The library is written entirely in JavaScript and can be used in the Node.JS environment.

This library attempts to show **best practices** in using [Sequelize.js](http://sequelizejs.com/). 

## Getting Started

```bash
# Clone the repository
git clone git@github.com:jpotts18/sequelize-starter.git

# Change into the repository root
cd sequelize-starter/

# Download and install an necessary dependencies 
npm install

# Start app.js using Grunt task runner. 
grunt

```

## NPM Modules
- [Passport](http://passportjs.org/) - Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more. 
- [Express](http://expressjs.com/) - Express is a minimal and flexible node.js web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Sequelize](http://sequelizejs.com/) - The Sequelize library provides easy access to MySQL, MariaDB, SQLite or PostgreSQL databases by mapping database entries to objects and vice versa. To put it in a nutshell, it's an ORM (Object-Relational-Mapper). The library is written entirely in JavaScript and can be used in the Node.JS environment. 

## Javascript Tools
- [Grunt](http://gruntjs.com/) - In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it, a Grunt can do most of that mundane work for you—and your team—with basically zero effort.

  1. It [watches](https://github.com/jpotts18/mean-stack-relational/blob/master/gruntfile.js#L5) your filesystem and when it detects a change it will livereload your changes. 

  2. It runs [jshint](https://github.com/jpotts18/mean-stack-relational/blob/master/gruntfile.js#L32) which looks through your javascript files and ensures coding standards.

  3. It runs [nodemon](https://github.com/jpotts18/mean-stack-relational/blob/master/gruntfile.js#L35) which watches changes in specific folders and recompiles the app when necessary. No running ```node app.js``` every 2 minutes. 

  4. It can also run tests like mocha and karma for you.

## Troubleshooting

During install some of you may encounter some issues feel free to contact me (jpotts18), via the repository issue tracker or the links provided below. I am also available on twitter [@jpotts18](http://twitter.com/jpotts18).





