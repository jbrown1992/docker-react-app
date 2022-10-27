## Docker

## Dev

### Build Image
docker build -f Dockerfile.dev -t jamesbrown/docker-react-app .

### See images
docker images

### Run image
docker run -it -p 3000:3000 jamesbrown/docker-react-app

## Prod

### Build image (gets default dockerfile)
docker build -t jamesbrown/docker-react-app .