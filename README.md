
![alt text][logo]


>A Application focused in customers registration.

This application was developed to be used by all who want to collect basic data of its future customers , and is designed to be used specifically for stands, fairs, shows, and other events.

The application is generic and customizable , it means that you can change your logotype , company name, and some other features.


## Installation

OS X & Linux:

##### [Mysql2](https://github.com/brianmario/mysql2)

##### in Linux

You may need to install a package such as `libmysqlclient-dev` or `mysql-devel`; refer to your distribution's package guide to find the particular package. The most common issue we see is a user who has the library file `libmysqlclient.so` but is missing the header file `mysql.h` -- double check that you have the -dev packages installed.

##### Mac OS X

You may use MacPorts, Homebrew, or a native MySQL installer package. The most common paths will be automatically searched. If you want to select a specific MySQL directory, use the `--with-mysql-dir` or `--with-mysql-config` options above.

##### Windows

Make sure that you have Ruby and the DevKit compilers installed. We recommend the [Ruby Installer](rubyinstaller.org) distribution.

By default, the mysql2 gem will download and use MySQL Connector/C from mysql.com. If you prefer to use a local installation of Connector/C, add the flag `--with-mysql-dir=c:/mysql-connector-c-x-y-z` (this path may use forward slashes).

By default, the `libmysql.dll` library will be copied into the mysql2 gem directory. To prevent this, add the flag `--no-vendor-libmysql`. The mysql2 gem will search for `libmysql.dll` in the following paths, in order:

    Environment variable `RUBY_MYSQL2_LIBMYSQL_DLL=C:\path\to\libmysql.dll` (note the Windows-style backslashes).
    In the mysql2 gem's own directory `vendor/libmysql.dll`
    In the system's default library search paths.

##### Installing

required the ruby version `2.3.1`

- Create the project folder `git clone https://github.com/henroca/visitor.git`

inside the project folder

- run `gem install bundler`

- run `bundle install`

- run `rake db:create`

- run `rake db:migrate`

- run `rails server`

- Accessing the page [here](http://localhost:3000/)

## System Resources

##### Current Update (Version: 0.0.0)

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
