# To perform Docker commands with push and pull commands.
 
# Push:
 Follow same steps as in exp-6


# 1. Tag the image for Docker Hub:

docker tag my-web-app:latest codewar77/my-web-app:latest

# 2. Log in to Docker Hub:

docker login

# 3. Push the image to Docker Hub:

docker push codewar77/my-web-app:latest

# Pull:
docker pull [OPTIONS] NAME[:TAG|@DIGEST]

docker pull nginx
