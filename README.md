## express-cloud-pipeline

Deployed application: https://express-cloud-pipeline.onrender.com

Every push to main builds the Docker image with GitHub Actions, pushes it to Docker Hub (ebencodex/express-cloud-pipeline) and triggers a new deployment on Render through a deploy hook.
