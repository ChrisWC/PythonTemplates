# PythonTemplates
Simple project to allow for definition of templates within python.

I'm starting this project to make it easier to work with boilerplate code, but
there are some other things I would like to experiment with in this code too.
-----------------------------------------------------------------------
Types

```
#Definition <File>
```
I'm suggesting that we have a definitions file that should contain the
definitions such as strings, processes, and scripts, to be used within the code.

It should also say how to use the 'definitions'. e.g. whether we should be pulling
the strings from the database with a language parameter.


-----------------------------------------------------------------------
Possible Syntax
template files should be have the suffix .pyt or .py.template

```
{% TemplateName <args> %}
```
```
#Template TemplateName <args>
```

```
...
```
---------------------------------------------------------------------------
