# Middleman Template: foundation5-kitchensink #

**foundation5-kitchensink** is a [Middleman](http://middlemanapp.com/) project template for the [ZURB Foundation 5](http://foundation.zurb.com/) Framework. The objective is to make a project that can quickly showcase the complete Foundation 5 stack including the Foundation Icon Fonts.

This project comes with some example files which uses:

1. [SASS](http://sass-lang.com/)
1. [Coffee Script](http://coffeescript.org/)
1. SMACSS folder structure

## Installation ##

Make sure to have:

1. ruby
1. git
1. middleman (`gem install middleman`)
1. bower (`npm install -g bower`) - npm depends on node.js so be sure to have it installed (e.g. via [homebrew](http://brew.sh) `brew install node`) 

Clone this repository to ~/.middleman

1. `git clone git://github.com/jamesrward/middleman-foundation5-kitchensink ~/.middleman/foundation5-kitchensink`
 
Then create a new project using the `foundation5-kitchensink` template. 

1. `middleman init my_new_project --template=foundation5-kitchensink`
1. `cd my_new_project`

Starting with Foundation 5, Zurb uses [bower](http://bower.io/) for the package management. The `bower install` command will create a folder `bower_components` with all needed files inside the source folder of Middleman. To prevent your git repository being polluted by changes to third party components, this directory is not tracked by git.  

1. `$ bower install`

Start the middleman server:

1. `$ bundle exec middleman`

Now you can start editing on the `source` directory and watch live changes on [localhost:4567](http://localhost:4567).