# Docker with and without Multistage Build
Here we will see what is the difference in the image size for the same application, when we create it using Multi-stage Docker file and without a multi-stage docker file.
<br />
<br />
![docke-multistaging-build2-1024x371](https://github.com/warlock601/Docker-Multistage/assets/32487715/1968a1d9-6968-4148-9a6e-f28e8648b475)

Clone this repository, go into the directory: dockerfile-without-multistage and then create a docker image without multistage-build. <br />
```bash
  docker build -t without-multistage .
```
Go back to main directory and then build multistage-build docker file.
```bash
  cd ..
  docker build -t multistage-build .
```

