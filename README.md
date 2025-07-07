gcloud projects add-iam-policy-binding calculator-465217 \
  --member="serviceAccount:github-actions@calculator-465217.iam.gserviceaccount.com \
  --role="roles/run.admin"

gcloud projects add-iam-policy-binding calculator-465217 \
  --member="serviceAccount:github-actions@calculator-465217.iam.gserviceaccount.com" \
  --role="roles/storage.admin"

gcloud projects add-iam-policy-binding calculator-465217 \
  --member="serviceAccount:github-actions@calculator-465217.iam.gserviceaccount.com" \
  --role="roles/artifactregistry.writer"
