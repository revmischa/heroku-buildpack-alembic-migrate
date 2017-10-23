This assumes there is an alembic config `alembic.ini`.

It runs `alembic upgrade head` in `$BUILD_DIR`.


Add to your build with:
`heroku buildpacks:add https://github.com/revmischa/heroku-buildpack-alembic-migrate.git`
