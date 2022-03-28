# gettingstarted-python

This is a very simple starter app for using UserCloud's Plex with Python

In order to make getting up and running even faster, we've included some test credentials in the code itself.These credentials won't actually do anything besides allow you to create an account and log into localhost, but
they should make things just a little bit easier.

We've also tried to simplify the code to the bare minimum to see what's going on, so please apply actual software
engineering practices to any code you write that derives from this!

As with any Python project, we'd recommend using a virtualenv to isolate dependencies ... we haven't included the virtualenv to avoid system-specific path issues.

```
python3 -m venv .
source bin/activate
pip3 install -r requirements.txt
```

See [Getting Started With Plex](https://userclouds.com/getting-started-with-plex) for a more detailed guide.
