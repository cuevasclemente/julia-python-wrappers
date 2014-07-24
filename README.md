julia-python-wrappers
=====================

With Julia being a newer language, there are many libraries that are unfortunately not yet written for it. There are also many libraries that are not as fully featured or well tested, which may present some difficulty for those of us using Julia in a production environment; in attempts to use Julia in production environments, written a number of wrappers around common python libraries for doing simple tasks faciliated by well-known python libraries. The hope in sharing these is that they might aid others who are embarking on similar ventures by saving perhaps minutes of productive time in seeking out facilities for the use of python libraries in Julia.

While the hope is for this repository to be obsolesced sooner rather than later, it appears to me, for the time being, a necessary evil in my personal work. 

# requestswrap.jl
Contains simple functions for sending requests in julia

# psycopgwrap.jl
Contains simple functions for using psycopg2 to interact with DBs in Julia by sending sql queries directly.

# xmlwrap.jl
Contains simple functions for using python's xml parser to parse XML.
