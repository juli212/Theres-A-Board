# There's A Board!

### Team Members

Jackie Feminella - jaclynfeminella@gmail.com
Julia Giraldi - jjgiraldi@gmail.com
Daniel Homer - daniel.homer6@gmail.com
John Seo - johndwseo@gmail.com


### Project Overview
3 day Dev Bootcamp project. Our stack is Ruby on Rails, PostgreSQL, JavaScript and Bootstrap.

Sparked by the surprisingly low-tech mentor scheduling system (a whiteboard), we resolved to streamline the signup process. Mentors and students alike can create profiles, post and sign up for appointments. All users can leave actionable, specific, and kind feedback on sessions.

# Getting Started

## 1. Clone There's A Board! repo from github.

        git clone git@github.com:juli212/Theres-A-Board.git
        
## 2. Create database user.

#### On OSX
If you're on OSX then you can run the following bootstrap task to setup your system with postgresql, npm, bundler and gulp. It will then create an admin user.

If you are setting up with PostgreSQL for the first time, you would have to create a superuser.

        [sudo] su postgres -c 'createuser -P --superuser <username>'

#### On Linux
If running Linux, you'll use:

        $ sudo -u postgres psql postgres
        postgres=# CREATE USER <youruseraccount> WITH SUPERUSER;
        \q
        $ logout

## 3. Install dependencies.
PubGamer uses [Bundler](http://gembundler.com/) to manage dependencies. If you don't have it, get it. Then install dependencies:
        
        gem install bundler
        bundle install

## 4. Set up database.

        rake db:create
        rake db:migrate

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
