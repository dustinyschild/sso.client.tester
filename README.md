# sso.client.tester

When using this the sso-client npm package, I came across what I thought was a bug.
This I am trying to reproduce what I was seeing and hopefully provide a fix if possible.

What I was seeing:
  Using the `.initialize()` method, I was sure I was seeing an appended `.then` method being called before the Promise was resolved.