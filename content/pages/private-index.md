Title: Private
Save_as: private/index.html
URL: private/

This page lives at /private/ and is gated by Cloudflare Access -- only
approved emails can get past the login screen to see it.

To add more pages under this path, give a new page in content/pages/ its
own Save_as (e.g. `private/notes/index.html`) and matching URL
(`private/notes/`). Anything under /private/* is covered by the same
Access policy automatically.
