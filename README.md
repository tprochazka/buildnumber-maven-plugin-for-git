buildnumber-maven-plugin-for-git
================================

This is clone of original buildnumber-maven-plugin which generate `${buildNumber}` as integer (commits count) instead of hash for GIT.

It is very usefull for Android development where `versionCode` must be always number.

If you want to use GIT commit hash new variable `${buildId}` was introduced.

For SVN will be `${buildNumber}` and `${buildId}` the same.

This version also allow set `buildNumberIncrement` configuration variable that will be add to the original `${buildNumber}`. This is very useful if you already have Android app on the Play store with bigger `versionCode` number that original `${buildNumber}` has.

 - Original plugin webpage: http://mojo.codehaus.org/buildnumber-maven-plugin/
 - Look here http://jira.codehaus.org/browse/MBUILDNUM-93 for more information.