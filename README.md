hello-grails
============

A hello world Grails 2.4.2 app that you can push to Stackato.

# Deploying

    grails war
    stackato target api.stackato-xxxx.local
    stackato login
    stackato push -n
