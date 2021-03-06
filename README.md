
![alt text][logo]

>A Application focused in customers registration.

This application was developed to be used by all who want to collect basic data of its future customers , and is designed to be used specifically for stands, fairs, shows, and other events.

The application is generic and customizable , it means that you can change your logotype , company name, and some other features.


## Installation

##### System Requirements:

- Gem [Mysql2](https://github.com/brianmario/mysql2)
- Ruby Version `2.3.1`.

Run this following Commands:

| Description| O. S. |Commands|
| :--: |:--:| :--:|
| Database Password| all |`export VISITOR_DATABASE_PASSWORD=mysql` |
| Create App Folder | all | `git clone https://github.com/henroca/visitor.git`|
| Database Socket | Mac OS X | `export VISITOR_DATABASE_SOCKET=/tmp/mysql.sock` |
| Database Socket | Linux | `export VISITOR_DATABASE_SOCKET=/var/run/mysqld/mysqld.sock` |

After this, run the following commands bellow inside the application folder:

- `bundle install`
- `rake db:create`
- `rake db:migrate`
- `rails s`
- [Run the application](http://localhost:3000/)

## System Resources

##### Current Update (Version: 0.0.1)

*Collaborator Dashboard*
- [ ] Customer Registration
- [ ] Client Details (Only Name and Registred by)
- [ ] Total Customers Registered (Database / By User) - (Only Number)

*Admin Dashboard*
- [ ] Collaborator Registration
- [ ] Customer Registration
- [ ] Client Details (Full Data)
- [ ] Total Customers Registered (Database / By User) - (Report)
- [ ] Raffle Machine


## Authors
- [Lucas Fernando Geron](https://github.com/lucasgeron "Github Profile")
- [Jose Mario de Souza Leão Júnior](https://github.com/MarioSL "Github Profile")
- [Jefesson Henrique Ramos](https://github.com/henroca "Github Profile")


[logo]: https://s31.postimg.org/rxdk5ar8r/Visitor_Logo_Black.png "Visitor Logo"
