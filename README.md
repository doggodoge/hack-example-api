# Hackathon Example API

This is a FastAPI project that you can use to get started with your project.
Included is an example of calling an API, and I've pre-configured CORS for
React. You can change your allowed origins based on what port your development
server uses.

## Install Dependencies

macOS/Linux

```shell
python3 -m pip install -r requirements.txt
```

Windows

```shell
py -m install -r requirements.txt
```

## Run the Server

This will start your API server. Making changes to the python code and saving
will automatically reload your changes, so long as you keep this running in
your terminal.

```shell
uvicorn main:app --reload
```

