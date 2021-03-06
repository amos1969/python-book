# Python Programming for Teachers and Students

These files are used to generate a [RunestoneInteractive](http://runestoneinteractive.org/) book. 

The files in this repository need to be pulled into an existing Runestone Book, in the _sources folder. If the user then 
runs:

```
runestone build
```

in the same folder, the files will be turned into the equivalent web pages.

If the user is using the [RunestoneComponents](https://github.com/RunestoneInteractive/RunestoneComponents) tools then they can then run:

```
runestone serve
```

at this point, to create a mini local server which will allow them to view the files locally.

If the user is using the [RunestoneServer](https://github.com/RunestoneInteractive/RunestoneServer) tools then they can run:

```
runestone deploy
```
to add the files to the local, **web2py** instance.  

Ideally I should be able to create a Flask App that will do the same sort of job, so that I can control how the output looks too.

Need to add some more chapters.
