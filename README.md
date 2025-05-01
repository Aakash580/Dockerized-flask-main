
### Prerequisite

- You have docker installed on your machine
- Basic knowledge about docker

## 1-Install docker

- See: [how-to-install-docker](https://github.com/tungbq/devops-basic/tree/main/topics/docker#how-to-install-docker)

## 2-Build the docker image

- Run `docker build -t my-flask-app .`

## Use the docker BuildX 
docker buildx build --load -t your-image-name .

## To push the image to a container registry (e.g., Docker Hub,ECR)
docker buildx build --push -t your-repo/your-image-name .
![Screenshot 2025-05-01 151826](https://github.com/user-attachments/assets/cb485891-45e7-43ba-bf15-49693c6e1a42)


## 3-Run the Docker container based on the image

- Run `docker run -p 5000:5000 my-flask-app`

## 4-Verify the result

- `curl localhost:5000`
- Or open http://localhost:5000/ in your browser

## Use the docker BuildX 
docker buildx build --load -t your-image-name .

## To push the image to a container registry (e.g., Docker Hub,ECR)
docker buildx build --push -t your-repo/your-image-name .

## Output 
![Screenshot 2025-05-01 151751](https://github.com/user-attachments/assets/70b40e1a-4064-475b-bdab-c72892d630fb)









