# In development.
this project is still in its very early stages, contact me if you're interested.

##ShuttleJS Frontend middleware
A special framework as a frontend middleware only.

##Key concepts
- covers frontend aspects only.
- runs in a cluster
- telemetry
- nodejs over express
- security
- view engines
- improvement over other frameworks I personally used in production.
- strong conventions in structure.

##CSS pipeline:
```
 compile css -> get all css classes -> map classes with uglified values
 compiled view -> replace css classes from mapped values.
```
##View pipeline:
```
 compile view -> mixins with with @static gets compiled into the production view.
              -> css replace to uglified version.
              -> 
```

