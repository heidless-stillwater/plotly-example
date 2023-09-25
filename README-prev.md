# tut
https://www.youtube.com/watch?v=1VewIO2Yhmo&list=PLY91jl6VVD7wLP84OUgmjGSUBbem92KHk&index=6

PLOTLY:
https://dash.plotly.com/layout



# Commands to build and deploy the application
```
#gcloud builds submit --tag gcr.io/ProjectID/dash-youtube-example  --project=ProjectID

gcloud builds submit --tag gcr.io/cloud-run-install/plotly-example  --project=cloud-run-install

#gcloud run deploy --image gcr.io/ProjectID/dash-youtube-example --platform managed  --project=ProjectID --allow-unauthenticated

gcloud run deploy --image gcr.io/cloud-run-install/plotly-example --platform managed  --project=cloud-run-install --allow-unauthenticated