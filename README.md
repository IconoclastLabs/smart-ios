smart-ios
=========

# Death Notice
## Don't use this anymore - After lots of spirited debate, RM 2.7+ comes with Bundler!
### See blog post on the release [here](http://blog.rubymotion.com/post/59390449567/new-in-rubymotion-versioning-bundler-run-on-device)


OLLLLLLLLLLLLLDDDD
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

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
  
