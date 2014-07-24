julia-python-wrappers
=====================

With Julia being a newer language, there are many libraries that are unfortunately not yet written for it. There are also many libraries that are not as fully featured or well tested as those available in languages that have had more time to develop, which may present some difficulty for those of us using Julia in a production environment; in attempts to use Julia in production environments I have out of necessity written a number of wrappers around common python libraries for doing simple tasks faciliated by a small handful of well-known python libraries. The hope in sharing these is that they might aid others who are embarking on similar ventures by saving perhaps minutes of productive time in seeking out facilities for the use of python libraries in Julia.

While the hope is for this work to be obsolesced sooner rather than later, it appears to me, for the time being, a necessary evil in my personal work. Once well documented libraries with APIs as simple and fully-featured as the Python APIs become commonplace for Julia, I would hope never to have to use these 

### requestswrap.jl
Contains simple functions for sending requests in julia

### psycopgwrap.jl
Contains simple functions for using psycopg2 to interact with Postgres Databases in Julia. Currently supports sending simple queries.

### xmlwrap.jl
Contains simple functions for using python's xml parser to parse XML.

### oauthwrap.jl
Combines functions from requestswrap and python's OAuthlib to facilitate using Julia as an OAuth Client.  
