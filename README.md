This assumes there is an alembic script `migrate.py`.

It runs `$PYTHON_EXE $BUILD_DIR/migrate.py db upgrade head`.


Add to your build with:
`heroku buildpacks:add https://github.com/revmischa/heroku-buildpack-alembic-migrate.git`
