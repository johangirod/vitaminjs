### Can I deploy vitamin to heroku?

Absolutely! From your application directory, you can set the buildpack like this:
```
$ heroku buildpacks set:https://github.com/victormours/heroku-buildpack-vitaminjs
```

And then just `git push heroku master`

And you're done!


### How to I log with vitaminJS ?

There is no logging system pre-installed 
