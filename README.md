## Graylog content pack for Heroku

This content pack spawns a TCP input on port 11003 with parsers that extract all request information and timings out of Heroku logs.

Add a syslog drain to your heroku application like this to receive your logs in Graylog: 

    $ heroku drains:add syslog://graylog2.example.com:11003
