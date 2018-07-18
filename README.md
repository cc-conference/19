# 18
27th International Conference on Compiler Construction 2018

# setting up website locally

Clone the git repository (change GIT_REPO_NAME): `git clone GIT_REPO_NAME`

Make sure to have the ruby header files installed on your system, then:

`gem install bundler`

`bundle install`

To build the website: `bundle exec jekyll build`

Then test it locally using a local webserver (this will make sure the website gets rebuilt automatically when any file changes):

`bundle exec jekyll serve --incremental`

Once done with changes:

`git commit -a`

`git push`

Check to see everything works: [https://cc-conference.github.io/18/]
