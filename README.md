# To perform Docker commands with push and pull commands.
 
# Push:
 Follow same steps as in exp-6


# 2. Tag the image for Docker Hub:

docker tag my-web-app:latest codewar77/my-web-app:latest

# 3. Log in to Docker Hub:

docker login

# 4. Push the image to Docker Hub:

docker push codewar77/my-web-app:latest

# Pull:

docker pull nginx
