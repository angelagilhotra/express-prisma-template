# template
forked from wall of love api
just backend

## add heroku remote 
`$ heroku git:remote -a <APP_NAME>` 

## add heroku url in env
`heroku config:set HEROKU_URL=$(heroku info -s | grep web_url | cut -d= -f2)`
