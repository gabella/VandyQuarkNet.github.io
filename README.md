# VandyQuarkNet.github.io
Web site describing the Vanderbilt QuarkNet Program for science enhancement in the high school classroom.
Right now (20190905) you get to it from https://gabella.github.com/VandyQuarkNet.github.io .

Trying to have a Vanderbilt QuarkNet website here that I could hand-off one day.  It is possible to have many Pages 
accounts from one login, something like gabella.github.com/VandyQuarkNet, but you have to "push" to the gh-pages.

In https://gist.github.com/mandiwise/44d1edce18f2ffb14f63 , says to keep up to date with gh-pages branch...

// Reference: http://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/

<pre>
$ git add .
$ git status // to see what changes are going to be commited
$ git commit -m 'Some descriptive commit message'
$ git push origin master

$ git checkout gh-pages // go to the gh-pages branch
$ git rebase master // bring gh-pages up to date with master
$ git push origin gh-pages // commit the changes
$ git checkout master // return to the master branch
</pre>
