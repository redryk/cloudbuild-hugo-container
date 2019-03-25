# HUGO - Docker container

## Deployment 

1. Replace [PROJECT_ID] in `cloudbuild.yaml` with your project id.
2. Run the following command on your terminal window:

```
gcloud builds submit --config=cloudbuild.yaml .
```