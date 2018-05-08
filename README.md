# gklsan-first-gem

Steps to create a gem

1) mkdir gklsan-first-gem && cd gklsan-first-gem

2) nano first_gem.gemspec  - write the required data

3) mkdir lib

4) nano lib/first_gem.rb - write your code here.

5) gem build first_gem.gemspec   - to build a gem

After that go to rails application

1) gem install first_gem-0.0.gem 

2) irb

3) require 'first_gem'

4) FirstGem::Welcome.welcome?
	
	o/p: Welcome to first gem by gokul.

