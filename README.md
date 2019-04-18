Flask-Sessionstore
==================

This project is a hard fork of the orphaned Flask-Session project at https://github.com/fengsp/flask-session that aims to provide 
python2 and python3 support for a growing number of session backends.

Flask-Sessionstore is an extension for Flask that adds support for Server-side Session to your application.

Please see the [Documentation](https://flask-sessionstore.rtfd.io) for implementation and configuration instruction. 

```bash
pip install flask-sessionstore
```

## Testing
Tests require a running version of MongoDB, Redis, and Memcached. The easiest way to get those 
is via docker-compose. 
```bash
$ docker-compose up -d
$ nosetests --with-timer
$ docker-compose down
```
