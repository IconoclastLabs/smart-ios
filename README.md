smart-ios
=========

A smarter starting template for RubyMotion that includes Bundler and its boilerplate to the Rakefile.

## About
The default current `motion create --template=ios` does not have bundler, and this makes me sad.

## Install and Use Template
You can use this template straight off github if you have RubyMotion >= 2.3

  `$ motion create --template=git@github.com:IconoclastLabs/smart-ios.git <myappname>`
  
This will pull down the template repo locally into your `~/Library/RubyMotion/template` path, and 
subsequent uses of the aforementioned `create` with this git url template will do a 
`git pull origin master` of this repo.

Once you've got the template locally, you can instead do:

   `$ motion create --template=smart-ios <myappname>`
   
But this will not invoke a git pull.
  
