(taken from the *traitlet-nolab* branch of [https://github.com/psychemedia/jupyterserverproxy-openrefine/tree/traitlet-nolab](https://github.com/psychemedia/jupyterserverproxy-openrefine/tree/traitlet-nolab))

# jupyterserverproxy-openrefine
Jupyter-server-proxy config for running OpenRefine

Start in OpenRefine client: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/psychemedia/jupyterserverproxy-openrefine/traitlet-nolab?urlpath=openrefine)

This `traitlet-nolab` branch demonstrates:

- using serverproxy (traitlet definition) to add an *OpenRefine* menu option to the notebook start menu. The configuration uses a fixed port assigment so that we can work with the client package.

OpenRefine can now be started and launched from the notebook homepage New menu.

![](Home-openrefinemenuitem.png)

The OpenRefine client can be found on the `openrefine` path or on a path explictly via the predefined port (`proxy/3333/`).

Calling the path directly (eg starting MyBinder with the path `openrefine`, or adding `?urlpath=openrefine` to the Bunder URL) will launch the Binder container directly into the OpenRefine GUI application.

Note that OpenRefine needs to be launched or otherwise started in order for it to be available to the Python Openrefine client.

Start on Jupyter notebook homepage: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/psychemedia/jupyterserverproxy-openrefine/traitlet-nolab)