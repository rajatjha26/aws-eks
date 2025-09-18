# FastAPI EKS Demo

This is a simple FastAPI app to test AWS CodePipeline CI/CD with:
- **CodeBuild** for Docker build & push to ECR
- **EKS** for deployment

## Endpoints
- `/` → returns a hello message
- `/health` → returns service status
