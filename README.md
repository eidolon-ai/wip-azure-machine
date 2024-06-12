# Eidolon Agent Machine Template

This project serves as a template for individuals interested in building agents with Eidolon.

## Directory Structure

- `resources`: This directory contains additional resources for the project. An example agent is provided for reference.
- `components`: This directory is where any custom code should be placed.

## Running the Server

First you need to clone the project and navigate to the project directory:

```bash
git clone https://github.com/eidolon-ai/agent-machine.git
cd agent-machine
```

Then run the server in dev mode, use the following command:

```bash
make serve-dev
```

This will start the Eidolon http server without MongoDB along with some other dev tools such as recordings. You may be 
prompted for environment variables as required by Makefile.

If the server starts successfully, you should see the following output:
```
Starting Server...
INFO:     Started server process [34623]
INFO:     Waiting for application startup.
INFO - Building machine 'local_dev'
...
INFO - Server Started in 1.50s
```
