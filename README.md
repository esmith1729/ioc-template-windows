# Template For epics-containers Generic IOC repositories

## To create a new Generic IOC

Activate a Python virtual environment, then:

```bash
pip install copier
# this will create a new folder ioc-MyNewProject
copier copy gh:epics-containers/ioc-template --trust ioc-MyNewProject
```
You will be asked for a few details and the resulting project is ready to push.

## To update an exising Generic IOC

Again you will need a virtual environment with `copier` installed.
cd into the project you wish to update and execute the following:

```bash
copier update --trust .
```
