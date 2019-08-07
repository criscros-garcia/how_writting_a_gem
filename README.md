How writting your first Ruby Gem¡
======
Following this lite tutorial you will be able to create your first gem structure.

	Writting a Ruby Gem with Bundler

	Bundler is a tool that help us to manage Rubygems dependencies. Was released around the same time as Rails 3 and was when people knew about it.

	But guess what?.  Bundler works fine for writting our owns gems as well. In other words bundler is a gem that helps us out to write gems. We better build a gem if we would like to use our code elsewhere or to share it. This lite tutorial was using version 2.0.2. So you might get different outputs, altough steps are the same in general.

So. Step number 1 is to install bundler gem.

Open your terminal and type: 
![alt text](https://github.com/criscros-garcia/how_writting_a_gem/blob/master/01_gem_install.png)

You can check your version by running the command:
$ bundle -v

Now that you have bundler already. You can use bundler to build gems. Think a name for your gem. In this case we will use “TicGarciaToc” as example.

$ bundle gem TicGarciaToe

	If it is your first time creating a gem you will be asked if you woulk like to include the next 3 files to your project(type yes/no): 

TESTS – Here you specify Rspec or minitest.
CODE OF CONDUCT – Code that is expected to be followed by all your gem contributors.
LICENSE. Includes the MIT license.


If you agree all of this. You would see a scafold structure like the next image.

!(https://github.com/criscros-garcia/how_writting_a_gem/blob/master/01_gem_name.png)
!(https://github.com/criscros-garcia/how_writting_a_gem/blob/master/03_gem_folders.png)

In this point your gem, folders and files were created.

You can use your favorite Code editor to view and edit your files.(Visual Studio Code, VIM, ATOM, Sublime Text, etc.)

