# lando-app

This instruction assumes that you have lando running on your development environment. That being said, please do the following commands:

1 - git clone
2 - cd lando-app
3 - lando init
4 - Enter
5 - Select Drupal9
6 - Type "web". Without the quotes
7 - Enter the app name: "lando-app"
8 - lando start
9 - lando composer install
10 - lando db-import db.sql.gz

After the commands, get hold of your domain using the lando info command.
Mine is: http://lando-app.lndo.site:8888/

And Voalla

You should be able to use the article API

http://lando-app.lndo.site:8888/

And by getting hold of the UUID, you can also get a resource:
https://example.org/jsonapi/node/article/{resourceId} where resourceId is the UUID