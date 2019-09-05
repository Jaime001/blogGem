# Blog

How create a Ruby gem with ***Bundler***?
First we need to know what is a gem in Ruby, how works, and finally how create and install the gem.

## What is a Ruby gem?

Well, the ***Ruby gem*** is a library for Ruby that are installed in the system and are left ready to being used and contains a piece of functionallity. 

# What contains a gem?

* .gemspec
* /lib
* Documentation

###### About .gemspec

> This file cointains all information about the gem, some of them are;
- Name
- Version
- Summary
- Authors
- License

###### About /lib
> This file contains the code of the gem, inside of this file, you can create your .rb

###### About Documentation
> Also, contain some documentation about of the gem in Code of conduct, and how install the gem in the README.md


## Now, what is Bundler?
> Bundler ensures that the gems you need are present in development, staging, and production. 
download in: https://bundler.io

## How install bundler?
Starting work on a project is as simple as: ***bundle install.***
Once time that we have Bundler installed in our PC, we can create a gem in this steps;
> Open your console and go to the directory that you want the gem. 
> Write this: bundle gem |Name|.

Next, automatically the gem will be created in the directory.

Inside of the folder, you can found the follow files:

* Bin
* Lib
* Spec
> rspec

> .gitignore

> |Name of the gem|.gemspec

> .travis.yml

> CODE_OF_CONDUCT.md

> Gemfile

> LICENSE.txt

> Rakefile

> README.md
  
## The gem are ready to be used.
