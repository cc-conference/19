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

J. Nelson Amaral, July 2018:

- As of now, I cannot figure out how the site is generated automatically. It seems that the layout files should be generated automatically. But I cannot see where the menus are specified. Thus, to remove the "Program" and "Attending" menus (for which we do not have content at the moment), I commented out the corresponding <li> entries in the file _layouts/default.html

- I also added CC18 to the "Previous CCs" at the bottom of the file _layouts/default.html
