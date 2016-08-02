# Heroku Multi Buildpack

Configure Heroku to use this multi buildpack:

```bash
$ heroku config:add BUILDPACK_URL=https://github.com/ceemion/heroku_multi_buildpack.git
```

## Usage
### Rails and Node.js application
Add the heroku-nodejs buildpack and heroku-ruby buildpack to **.buildpacks** at your application root directory:
```bash
$ cat .buildpacks
https://github.com/heroku/heroku-buildpack-nodejs
https://github.com/heroku/heroku-buildpack-ruby
```

## Credit
https://github.com/ddollar/heroku-buildpack-multi
