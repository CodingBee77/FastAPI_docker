# FastAPI_docker

This is a simple Fast API application which runs in a docker container.

![Image1](readme_images/fastapi.png)


![Image2](readme_images/docker.png)


It has only 2 endpoints for a demonstration purposes.

![Image3](readme_images/fastapi_docs.png)

As dependency manager  Poetry library was used.

![Image4](readme_images/poetry.png)

------------------------------------------------

To build and run app in the container:

- download folder FastAPI_docker
- enter folder
- run: 

```
docker-compose up
```

Enter localhost:0.0.0.0 in your webbrowser.
If any issue appear - try to map different port in docker compose file ( line 12 ).
