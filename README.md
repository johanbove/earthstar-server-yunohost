# Earthstar Server for Yunohost

This template will help you deploy an Earthstar server on a Yunohost server as an installable application. The server
will run on the Deno runtime.

Read [the Yunohost documentation](https://yunohost.org/en/packaging_manifest) on how this application package was created.

If you'd like to further customise your server, you can learn more about servers
and their extensions at the
[main Earthstar repo](https://github.com/earthstar-project/earthstar/blob/main/README_SERVERS.md).

## Initial deployment

1. Create a new file called `known_shares.json` in the root of this project. Add
   the public addresses of the shares you'd like your server to replicate as an
   array of strings (e.g. `["+one.xxx", "+two.xxx"]`).

## Running locally

You might want to make some changes and test them locally. You'll need to have
Deno installed to do it
([instructions here](https://deno.land/manual/getting_started/installation)).
You can do that by running the following:

```
deno task server
```
