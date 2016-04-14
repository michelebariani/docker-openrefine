# docker-openrefine
----

A Dockerfile yielding a container for OpenRefine (code from [GitHub OpenRefine][1], currently v2.6-rc2).


Run the container
-----------------
Example keeping same exposed port:

     docker run -d -p 3333:3333 --name=openefine mbariani/openrefine


[1]: https://github.com/OpenRefine
