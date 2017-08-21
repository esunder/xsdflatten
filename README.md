# xsdflatten
Rudimentary python script to flatten an xsd schema into a single document. Flattened schema is printed to the console.

# dependencies
```pip install lxml```

# usage
```xsdflatten.py <schema_document_to_flatten> > flattened.xsd```

# troubleshooting
If you have issues after installing lxml on Mac, you might try resetting the PATH:

Apparently, LXML Install on a Mac ends up installing it in the wrong path, so you have to reset the path using:

```export PATH="/Library/Frameworks/Python.framework/Versions/2.7/bin:${PATH}"```

See more details: https://stackoverflow.com/questions/27008222/importerror-no-module-named-lxml-even-though-lxml-is-installed
