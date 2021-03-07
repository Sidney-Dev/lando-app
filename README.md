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