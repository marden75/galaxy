
**Ruby on rails Rails application with  React as V-component **
===================
![Reactive Rails!](https://geeks.wego.com/content/images/2015/12/eed49439b4a4d36167ef4aa568beb94f.jpg)

### Specifications:


----------

> ### **Technologies we used:**
 -  **Ruby on rails** 
 - **React.js** 
 - **Redux**
 - **Axios** 
 - **JQuery**
 - **Bootstrap** 
 - **Node.js**
 - **NPM**


 
> ### **Configuration scripts**
 - `postinstall:` "cd app/assets/webpack && npm i",
 - `start:` "foreman start",
 - `build:` "sh -c 'rm app/assets/webpack/dist/* || true && foreman run bin/rails > - assets:precompile'",
 - `start:dev:` "foreman start -f Procfile.dev",
 - `build:dev:` "sh -c 'rm app/assets/webpack/dist/* || true && cd app/assets/webpack && npm run build:development'",
 - `rails:` "foreman run bin/rails",
 - `test:` "foreman run bin/rails test"

 >### **About** 
 >>- *Ruby on Rails*
- *Ruby on Rails, or simply Rails, is a server-side web application framework written in Ruby under the MIT License. Rails is a model–view–controller (MVC) framework, providing default structures for a database, a web service, and web pages. It encourages and facilitates the use of web standards such as JSON or XML for data transfer, and HTML, CSS and JavaScript for display and user interfacing. In addition to MVC, Rails emphasizes the use of other well-known software engineering patterns and paradigms, including convention over configuration (CoC), don't repeat yourself (DRY), and the active record pattern.*

 >>- *React JS*
- *It is maintained by Facebook, Instagram and a community of individual developers and corporations. According to JavaScript analytics service Libscore, React is currently being used on the websites of Netflix, Imgur, Bleacher Report, Feedly, Airbnb, SeatGeek, HelloSign, Walmart, Portfolio's, Paviljons Concept Store and others.*

# Social network service
[*Ruby, Rails, React, Redux, Webpack*]
***
# Basic Demo Setup

#### *Preparation*
> App uses PostgreSQL. You need change config in database.yml or create new pg_user:
#
```sh
$ sudo -u postgres createuser -s rails_user
$ sudo -u postgres psql
in postgres=#
$ \password rails_user
$ password
$ password
$ \q
```

#### *Install*
1.Open terminal window in *backend* folder and run:

```sh
a)bundle install
b)rake db:setup
c)rails s
```
2.Open next terminal window in *frontend* folder and run:

```sh
a) npm install `or` sudo npm install
b) npm start
```
3.Wait to start all servers

4.Visit http://localhost:8080

5.Create new user or login as demo-user:
> [*email:* my_email@exemple.com, *password:* Truepass1]


***
#
# Run test

***

### *Rails test*

[*controllers, models, mailer, helpers test*]

* Open terminal window in *backend* folder and run: `rails test test`

***

### *Some react classes test*

[*Jest*]

* Open terminal window in *frontend* folder and run: `npm test`

***

### *Integration test*

[*Protractor, Chrome, Jasmine*]

* Open terminal window in *backend* folder and run: `rails s`
* Open next terminal window in *frontend* folder and run: `npm start`
* Open next terminal window in *frontend* folder again and run: `npm run integration`

> If test don't run, update your webDriver: run `./node_modules/protractor/bin/webdriver-manager update` and `webdriver-manager update`.
