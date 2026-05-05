# Personal Portfolio — Hosted on GCP Cloud Storage

A personal portfolio website deployed and hosted live on Google Cloud Platform using Cloud Storage static website hosting.

🌐 **Live URL:** https://storage.googleapis.com/andrawis_portfolio/index.html

## Project Overview

This project demonstrates deploying a static website on GCP Cloud Storage with public access configuration — entirely through the GCP Console and Cloud Shell CLI.

## Technologies Used

- **Google Cloud Platform (GCP)**
- **Cloud Storage** — static website hosting
- **Cloud Shell CLI (gsutil)** — bucket configuration
- **HTML / CSS** — frontend

## Steps Performed

1. Created a **Cloud Storage bucket** (`andrawis_portfolio`) via GCP Console
2. Uploaded `index.html` and `profile.jpg` to the bucket
3. Configured **public access** by granting `allUsers` the Storage Object Viewer role
4. Set **website configuration** using Cloud Shell CLI:
   ```
   gsutil web set -m index.html gs://andrawis_portfolio
   ```
5. Verified the portfolio is publicly accessible via the storage URL

## Key Concepts Demonstrated

- GCP Cloud Storage bucket creation and management
- Static website hosting on cloud object storage
- Public access configuration and IAM permissions
- CLI-based bucket configuration with gsutil
- Cloud deployment workflow end-to-end

---
*Part of my cloud engineering learning path — Build with AI Masr Edition (GDG × ITI)*
