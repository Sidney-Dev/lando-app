# lando-app

This instruction assumes that you have lando running on your development environment. That being said, please do the following commands:

<p>1 - git clone</p>
<p>2 - cd lando-app</p>
<p>3 - lando init</p>
<p>4 - Enter</p>
<p>5 - Select Drupal9</p>
<p>6 - Type "web". Without the quotes</p>
<p>7 - Enter the app name: "lando-app"</p>
<p>8 - lando start<p>
<p>9 - lando composer install</p>
<p>10 - lando db-import db.sql.gz</p>

<p>After the commands, get hold of your domain using the lando info command.</p>
<p>Mine is: http://lando-app.lndo.site:8888/</p>

<p>And Voalla</p>

<p>You should be able to use the article API</p>

<p>http://lando-app.lndo.site:8888/<//p>

<p>And by getting hold of the UUID, you can also get a resource:<p>
<p>https://example.org/jsonapi/node/article/{resourceId} where resourceId is the UUID</p>
<p>use <b>abad9cd6-7597-483d-a634-485a88cbcc55</b> to view an article</p>.
<p><b>Example: </b>http://lando-app.lndo.site:8888/jsonapi/node/article/abad9cd6-7597-483d-a634-485a88cbcc55</p>

<h3>More resource IDs</h3>
<p>To get resourceId(UUID), visit http://lando-app.lndo.site:8888/devel/node/ID</p>
<p>where ID is to be replaced by the node ID for the content you want</p>
<p>Under the "load tab" expand the "variable", and check for the UUID available to you</p>

<h3>Use Drush to login to the administration panel</h3>
<p>Enter the following command to your console: <b>lando drush uli</b></p>
<p>The console will give you: http://default/user/reset/1/1615298481/CasxZev_YacSD8SLXZU8Xdv1Tx4ZuISzLw8IyPorLs0/login </p>
<p>Replace the "default" string for your lando domain <br> and you should have something like this: http://lando-app.lndo.site:8888/user/reset/1/1615298481/CasxZev_YacSD8SLXZU8Xdv1Tx4ZuISzLw8IyPorLs0/login</p>

<h3>Alternatively, you can login using the username and password</h3>
<p>username: sidney-admin; password: 12345678</p>