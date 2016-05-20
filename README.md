Forked from [octopress/solarized](https://github.com/octopress/solarized).

Changes:

- Custom stylesheets/scss


## To build

     rake build_css
     gem build octopress-solarized.gemspec
     gem install octopress-solarized-1.1.2.gem
 
 When included as a gem in a octopress website, make sure the gem is pointed to the url with correct tagging.
 
    gem 'octopress-solarized', :git => 'https://github.com/samwize/solarized', :tag => 'v1.1.2z'
    