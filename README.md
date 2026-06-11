# CS446 Cloud Computing Coursework Portfolio

This repository is a portfolio collection of CS446 Cloud Computing assignments and labs. It brings together written reports, LaTeX source files, cloud deployment code, Kubernetes manifests, Terraform configurations, serverless functions, screenshots, and supporting scripts from a full cloud computing course sequence.

The work focuses mainly on Google Cloud Platform and covers foundational cloud setup, virtual machines, networking, storage, databases, serverless computing, containers, Kubernetes, IAM security, infrastructure as code, NLP cloud services, Vertex AI, Cloud Build, Cloud Run, and CI/CD deployment workflows.

## Repository Name Recommendation

```text
cs446-cloud-computing-coursework-portfolio
```

## GitHub Short Description

```text
CS446 cloud computing portfolio with GCP assignments and labs covering Compute Engine, Cloud Storage, Cloud SQL, Cloud Functions, Docker, Kubernetes, GKE, IAM, Terraform, Vertex AI, Cloud Run, and CI/CD.
```

## Repository Overview

This repository is intended to be a single place where the full CS446 cloud computing coursework can be viewed. The files include two main types of work.

First, the assignment files are larger report based projects. These usually include PDF reports, LaTeX source archives, screenshots, and sometimes application or infrastructure code.

Second, the lab files are hands on technical exercises. These include code, scripts, screenshots, Terraform files, Google Cloud Function source code, Kubernetes YAML files, and deployment evidence.

Together, the files show practical experience with cloud resource provisioning, cloud networking, managed services, containerization, orchestration, cloud security, infrastructure automation, and deployment pipelines.

## Skills Demonstrated

- Google Cloud Platform setup and management
- Cloud billing and budget alert configuration
- Compute Engine virtual machine deployment
- Cloud Storage bucket management
- Cloud SQL and PostgreSQL usage
- Firestore document storage
- Cloud Functions and event driven serverless workflows
- Cloud Vision API integration
- Cloud Natural Language API integration
- Vertex AI model deployment workflow
- Docker image creation
- Docker Compose multi service orchestration
- Kubernetes deployments, services, probes, and scaling
- Google Kubernetes Engine deployment
- IAM least privilege design
- Service accounts and service account impersonation
- IAM Conditions and custom roles
- Terraform based infrastructure as code
- Cloud Build and Artifact Registry workflows
- Cloud Run deployment
- CI/CD and GitOps style deployment evidence
- Technical documentation with LaTeX and PDF reports

## Files Included

### Assignment Files

| File | Description |
| --- | --- |
| `Stys_Jason_A1_CS446.pdf` | Assignment 1 report covering cloud foundation setup, project creation, billing alerts, gcloud configuration, Compute Engine API access, and Cloud Storage CLI usage. |
| `Stys_Jason_A1_CS446.zip` | LaTeX source and screenshot evidence for Assignment 1. |
| `Stys_Jason_A2_Cloud_OverleafProject.pdf` | Assignment 2 report covering cloud hosted web servers, VM architecture, regional latency testing, and load balancing. |
| `Stys_Jason_A2_Cloud_OverleafProject.zip` | LaTeX source, bibliography, and screenshot evidence for Assignment 2. |
| `Stys_Jason_A3_CS446.pdf` | Assignment 3 report covering a secure multi tier Google Cloud network for a web and database architecture. |
| `Stys_Jason_A3_CS446.zip` | LaTeX source, references, diagrams, and screenshot evidence for Assignment 3. |
| `Stys_Jason_A4_CS446.tex` | Assignment 4 LaTeX report source for a Docker and Kubernetes machine learning application deployment. |
| `Stys Jason A4 CS446.zip` | Flask, Docker, Docker Compose, Redis, machine learning, and Kubernetes source files for Assignment 4. |
| `Stys_Jason_A5_CS446.pdf` | Assignment 5 report covering deployment of a containerized application to Google Kubernetes Engine. |
| `Stys_Jason_A5_CS446_laTex.zip` | Assignment 5 LaTeX source, Kubernetes manifests, autoscaler manifest, service manifest, deployment manifest, and screenshot evidence. |

### Lab Files

| File | Description |
| --- | --- |
| `Stys_Jason_week8_lab.zip` | Week 8 Cloud Functions lab with HTTP, Cloud Storage trigger, and Vision API image analysis functions. |
| `cloud_computing_week9_lab_files.zip` | Week 9 code files for Cloud SQL, PostgreSQL, Python database access, Cloud Functions, Vision API, and Firestore. |
| `cloud_computing_week9_lab_screenshots.zip` | Week 9 screenshot evidence for both labs and cleanup. |
| `Week10_NLP_Lab_Code_Files.zip` | Week 10 NLP lab code for Cloud Natural Language API, event driven text analysis, and a BiLSTM sentiment model workflow for Vertex AI. |
| `Week 10_NLP_Lab_Screenshots.zip` | Week 10 screenshot evidence for function deployment, NLP analysis, model deployment, endpoint testing, and cleanup. |
| `Cloud_Computing_Week12_Lab_Screenshots.zip` | Week 12 IAM and cloud security lab screenshots covering least privilege, IAM Conditions, custom roles, and service account impersonation. |
| `terraform_week13_lab_files.zip` | Week 13 Terraform files for GCP networking, VM creation, firewall rules, variables, outputs, and Apache web server provisioning. |
| `terraform_week13_screenshots.zip` | Week 13 screenshot evidence for Terraform init, plan, apply, outputs, curl tests, instance verification, and destroy workflows. |
| `week14_cicd_lab_screenshots.zip` | Week 14 CI/CD screenshots covering pytest, Artifact Registry, Cloud Build, Cloud Run, Terraform validation, GitOps deployment, rollback, and cleanup. |

## Assignment Summaries

## Assignment 1: Cloud Foundation and GCP Setup

Assignment 1 establishes the basic Google Cloud development environment. The report covers core cloud computing concepts and documents the setup of a GCP project, billing safety controls, and command line access.

The work includes account access, project creation, budget alert setup, `gcloud` CLI initialization, Compute Engine API enablement, and Cloud Storage CLI commands. The included screenshots document the project dashboard, project information, budget alert configuration, gcloud configuration output, Compute Engine API status, and storage command usage.

This assignment demonstrates the ability to prepare a cloud project safely and verify that core services are ready before deploying workloads.

Key topics include:

- Cloud service models
- Cloud economic impact
- Cloud deployment models
- Google Cloud project setup
- Budget alert configuration
- `gcloud` CLI setup
- Compute Engine API enablement
- Cloud Storage CLI verification

Related files:

```text
Stys_Jason_A1_CS446.pdf
Stys_Jason_A1_CS446.zip
```

## Assignment 2: Launching a Web Server in the Cloud

Assignment 2 focuses on deploying a basic web server using Google Compute Engine. The report documents a Linux VM running Nginx, then expands into a multi VM architecture with front end and back end instances.

The project also explores cloud geography and network latency by testing systems across regions. It includes load balancing concepts and documents public browser verification of the deployed web service.

This assignment demonstrates basic infrastructure deployment, remote server configuration, public access testing, and the relationship between region choice and latency.

Key topics include:

- Compute Engine VM deployment
- Linux server setup
- Nginx web server installation
- Front end and back end VM architecture
- Regional latency testing
- Load balancing concepts
- Public browser verification
- Screenshot based deployment evidence

Related files:

```text
Stys_Jason_A2_Cloud_OverleafProject.pdf
Stys_Jason_A2_Cloud_OverleafProject.zip
```

## Assignment 3: Secure Multi Tier Cloud Network

Assignment 3 designs and implements a secure multi tier Google Cloud network for a fictional organization called TerraSync Media. The architecture separates a public web tier from a private database tier using a custom VPC and regional subnets.

The project uses firewall rules to enforce least privilege. HTTP is allowed to the web tier, database traffic is allowed only from the web tier, and administrative access is limited through trusted ranges and IAP tunneling. The assignment also includes object storage with a lifecycle policy, SSD persistent disk storage for the database VM, and a second region web deployment.

This assignment demonstrates secure cloud architecture design and practical network segmentation.

Key topics include:

- Custom mode VPC design
- Regional subnets
- Public web subnet
- Private database subnet
- No external IP database configuration
- Firewall rules with network tags
- IAP based administration
- Cloud Storage lifecycle policies
- SSD persistent disk attachment and mounting
- Multi region expansion
- Startup script automation

Related files:

```text
Stys_Jason_A3_CS446.pdf
Stys_Jason_A3_CS446.zip
```

## Assignment 4: Containerized Machine Learning Web App

Assignment 4 containerizes a machine learning prediction service. The application uses Flask to serve an Iris classifier and Redis to store a persistent prediction counter. The project includes a Dockerfile, Docker Compose configuration, Flask templates, a model training script, and Kubernetes deployment files.

The Docker workflow packages the application and dependencies into a reproducible image. Docker Compose runs the Flask app and Redis together on a shared network. The Kubernetes manifests translate the same application design into deployments and services with health checks, readiness checks, resource limits, and multiple web app replicas.

This assignment demonstrates how a local machine learning application can be turned into a portable containerized service and prepared for orchestration.

Key topics include:

- Flask web application development
- Iris classifier training with scikit-learn
- Model serialization with joblib
- Redis backed request counting
- Dockerfile creation
- Docker Compose multi container setup
- Kubernetes Deployment manifests
- Kubernetes Service manifests
- Liveness and readiness probes
- Resource requests and limits
- NodePort service exposure

Related files:

```text
Stys_Jason_A4_CS446.tex
Stys Jason A4 CS446.zip
```

Important source files inside the Assignment 4 archive include:

```text
ml-app/app.py
ml-app/train_model.py
ml-app/Dockerfile
ml-app/docker-compose.yml
ml-app/requirements.txt
ml-app/templates/index.html
ml-app/templates/result.html
k8s/webapp-deployment.yaml
k8s/webapp-service.yaml
k8s/redis-deployment.yaml
k8s/redis-service.yaml
```

## Assignment 5: Google Kubernetes Engine Deployment

Assignment 5 deploys a containerized web application to Google Kubernetes Engine. The project moves beyond local Docker and Kubernetes manifests by using a managed Kubernetes cluster.

The report documents creating and configuring a GKE cluster, applying Kubernetes Deployment and Service manifests, exposing the application through a public load balancer, verifying pods and services, testing the application in a browser, enabling horizontal pod autoscaling, and demonstrating rolling updates.

This assignment demonstrates practical container orchestration in a managed cloud environment.

Key topics include:

- Google Kubernetes Engine
- Kubernetes Deployments
- Kubernetes Services
- Public LoadBalancer service
- Redis ClusterIP service
- Web application replicas
- Liveness and readiness probes
- Horizontal Pod Autoscaler
- CPU based scaling
- Rolling update strategy
- `kubectl` verification commands
- Browser based application testing

Related files:

```text
Stys_Jason_A5_CS446.pdf
Stys_Jason_A5_CS446_laTex.zip
```

Important source files inside the Assignment 5 archive include:

```text
deployment.yaml
service.yaml
hpa.yaml
main.tex
```

## Lab Summaries

## Week 8 Lab: Cloud Functions and Event Driven Processing

The Week 8 lab explores Google Cloud Functions through three serverless examples.

Lab 1 deploys an HTTP Cloud Function that returns a simple message. Lab 2 deploys a Cloud Storage triggered function that logs object upload events. Lab 3 deploys an image analysis function that uses the Cloud Vision API to label an uploaded image and write the results to an output Cloud Storage bucket.

This lab demonstrates event driven cloud programming and basic serverless deployment workflows.

Key topics include:

- Google Cloud Functions
- HTTP triggers
- Cloud Storage finalize triggers
- Cloud Vision API
- Environment variables
- Deployment scripts
- Test scripts
- Cloud Storage input and output buckets

Related files:

```text
Stys_Jason_week8_lab.zip
```

Important files inside the archive include:

```text
lab1_http/main.py
lab1_http/deploy.sh
lab1_http/test.sh
lab2_gcs_trigger/main.py
lab2_gcs_trigger/deploy.sh
lab2_gcs_trigger/test.sh
lab3_image_analysis/main.py
lab3_image_analysis/deploy.sh
lab3_image_analysis/test.sh
lab3_image_analysis/requirements.txt
sample_outputs/results-sample-image.jpg.txt
```

## Week 9 Lab: Cloud SQL, Firestore, Vision API, and Serverless Data Processing

The Week 9 lab includes two main parts.

Lab 1 creates a Cloud SQL PostgreSQL workflow for a student enrollment database. It includes schema creation, sample data insertion, query scripts, and a Python application that uses `psycopg2` and a connection pool to interact with the database.

Lab 2 uses a Cloud Function with the Vision API and Firestore. When an image is uploaded to Cloud Storage, the function extracts text from the image and writes the result to a Firestore collection.

This lab demonstrates managed database usage, SQL modeling, Python database connectivity, and event driven image text extraction.

Key topics include:

- Cloud SQL PostgreSQL
- Private services access
- Bastion VM database access
- SQL schema design
- Sample data insertion
- SQL joins and aggregate queries
- Python database connection pooling
- Cloud Functions
- Cloud Vision document text detection
- Firestore writes
- Cloud Storage event triggers

Related files:

```text
cloud_computing_week9_lab_files.zip
cloud_computing_week9_lab_screenshots.zip
```

Important files inside the code archive include:

```text
lab_code_files/Lab1/lab1_schema.sql
lab_code_files/Lab1/lab1_sample_data.sql
lab_code_files/Lab1/lab1_queries.sql
lab_code_files/Lab1/lab1_app.py
lab_code_files/Lab2/main.py
lab_code_files/Lab2/requirements.txt
lab_code_files/commands_used.txt
```

## Week 10 Lab: Cloud NLP and Vertex AI Sentiment Workflow

The Week 10 lab focuses on natural language processing in the cloud.

Lab 1 uses the Google Cloud Natural Language API for sentiment and entity extraction. It includes a standalone script for testing sample text and an event driven Cloud Function that analyzes text files uploaded to Cloud Storage, then stores sentiment and entity results in Firestore.

Lab 2 builds a BiLSTM based IMDB sentiment classifier workflow. The code preprocesses text, builds sequences, loads GloVe embeddings, trains a bidirectional LSTM sentiment model, evaluates it, and prepares an example request payload for Vertex AI online prediction.

This lab demonstrates both managed NLP APIs and custom machine learning deployment workflows.

Key topics include:

- Cloud Natural Language API
- Sentiment analysis
- Entity extraction
- Cloud Function text processing
- Firestore result storage
- TensorFlow text classification
- IMDB sentiment dataset
- GloVe word embeddings
- Bidirectional LSTM model
- Vertex AI deployment workflow
- Online prediction request payloads

Related files:

```text
Week10_NLP_Lab_Code_Files.zip
Week 10_NLP_Lab_Screenshots.zip
```

Important files inside the code archive include:

```text
Lab_1/sentiment_entities.py
Lab_1/cloud_function/main.py
Lab_1/cloud_function/requirements.txt
Lab_1/test_files/
Lab_2/imdb_bilstm_vertex_ai.py
Lab_2/imdb_bilstm_vertex_ai_notebook.ipynb
Lab_2/requirements.txt
Lab_2/request.json
```

## Week 12 Lab: IAM, Least Privilege, and Service Account Security

The Week 12 lab is a cloud security focused lab using screenshot evidence. The screenshot names show exercises involving IAM role scope, least privilege, service accounts, IAM Conditions, custom roles, separation of duties, permission denial validation, and service account impersonation.

The lab contrasts wrong way and right way access patterns. Examples include broad project editor access versus granular roles, overly broad object admin permissions versus custom role separation, and JSON service account keys versus service account impersonation.

This lab demonstrates practical cloud access control and identity security.

Key topics include:

- IAM least privilege
- Project level role risk
- Granular role assignment
- IAM Conditions
- Prefix scoped access to Cloud Storage uploads
- Custom roles
- Separation of duties
- Permission denied testing
- Service account setup
- Service account impersonation
- Avoiding long lived JSON keys

Related files:

```text
Cloud_Computing_Week12_Lab_Screenshots.zip
```

Screenshot evidence includes:

```text
Lab_1_wrong_way_project_editor_1.png
Lab_1_right_way_granular_roles_1.png
Lab_1_iam_conditions_uploads_prefix_1.png
Lab_1_condition_enforcement_error_1.png
Lab_2_wrong_way_object_admin_1.png
Lab_2_custom_role_separation_of_duties_1.png
Lab_2_successful_separation_validation_1.png
Lab_3_wrong_way_json_key_1.png
Lab_3_service_account_impersonation_1.png
Lab_3_impersonation_success_bucket_access_1.png
```

## Week 13 Lab: Terraform Infrastructure as Code

The Week 13 lab uses Terraform to provision Google Cloud infrastructure.

Lab 1 creates a basic Terraform managed GCP network, firewall rule, and Compute Engine VM. Lab 2 improves the design with variables, outputs, HTTP firewall access, and a startup script that installs Apache and serves a simple web page.

The screenshots document the Terraform lifecycle, including initialization, planning, applying, output verification, curl testing, instance list checks, and resource destruction.

This lab demonstrates infrastructure as code and repeatable cloud provisioning.

Key topics include:

- Terraform Google provider
- GCP network creation
- Compute Engine VM provisioning
- Firewall rule management
- Variables
- Outputs
- Apache startup script
- Terraform init, plan, apply, and destroy
- Curl based service verification

Related files:

```text
terraform_week13_lab_files.zip
terraform_week13_screenshots.zip
```

Important files inside the code archive include:

```text
terraform-week13-lab1/main.tf
terraform-week13-lab2/main.tf
terraform-week13-lab2/variables.tf
terraform-week13-lab2/outputs.tf
```

## Week 14 Lab: CI/CD, Cloud Build, Cloud Run, and GitOps Style Deployment

The Week 14 lab focuses on automated build and deployment workflows.

The screenshot archive shows two labs. Lab 1 creates application files, runs pytest, enables required APIs, creates an Artifact Registry repository, grants Cloud Build permissions, submits a Cloud Build, deploys to Cloud Run, verifies the service URL with curl, checks revisions, and cleans up resources.

Lab 2 uses Terraform and Cloud Build for a GitOps style workflow. It includes Terraform init, validation, planning, applying resources, verifying deployed resources, pushing code to trigger Cloud Build, deploying through a Git based workflow, rolling back, and destroying resources.

This lab demonstrates modern DevOps and CI/CD practices on Google Cloud.

Key topics include:

- Automated testing with pytest
- Artifact Registry
- Cloud Build
- Cloud Run deployment
- IAM permissions for build pipelines
- Service URL verification
- Cloud Run revisions
- Terraform validation and plan
- Git triggered deployment
- GitOps style workflow
- Rollback and cleanup

Related files:

```text
week14_cicd_lab_screenshots.zip
```

Screenshot evidence includes:

```text
01_lab1_create_app_files_and_run_pytest.png
02_lab1_enable_apis_and_create_artifact_registry_repo.png
03_lab1_grant_cloud_build_iam_permissions.png
04_lab1_submit_cloud_build_and_deploy_to_cloud_run.png
05_lab1_verify_cloud_build_url_curl_and_revision.png
06_lab1_cleanup_cloud_run_and_artifact_registry.png
07_lab2_terraform_init_validate_and_plan.png
08_lab2_terraform_apply_and_verify_resources.png
09_lab2_git_push_triggers_cloud_build_gitops_deploy.png
10_lab2_rollback_and_destroy_resources.png
```

## Suggested Repository Organization

The uploaded files can be committed exactly as provided, but the repository will be easier to browse if the files are organized into folders like this:

```text
.
├── README.md
├── assignments/
│   ├── assignment-01-cloud-foundation/
│   │   ├── Stys_Jason_A1_CS446.pdf
│   │   └── Stys_Jason_A1_CS446.zip
│   ├── assignment-02-web-server/
│   │   ├── Stys_Jason_A2_Cloud_OverleafProject.pdf
│   │   └── Stys_Jason_A2_Cloud_OverleafProject.zip
│   ├── assignment-03-secure-cloud-network/
│   │   ├── Stys_Jason_A3_CS446.pdf
│   │   └── Stys_Jason_A3_CS446.zip
│   ├── assignment-04-containerized-ml-app/
│   │   ├── Stys_Jason_A4_CS446.tex
│   │   └── Stys Jason A4 CS446.zip
│   └── assignment-05-gke-deployment/
│       ├── Stys_Jason_A5_CS446.pdf
│       └── Stys_Jason_A5_CS446_laTex.zip
└── labs/
    ├── week-08-cloud-functions/
    │   └── Stys_Jason_week8_lab.zip
    ├── week-09-cloud-sql-functions-firestore/
    │   ├── cloud_computing_week9_lab_files.zip
    │   └── cloud_computing_week9_lab_screenshots.zip
    ├── week-10-cloud-nlp-vertex-ai/
    │   ├── Week10_NLP_Lab_Code_Files.zip
    │   └── Week 10_NLP_Lab_Screenshots.zip
    ├── week-12-iam-security/
    │   └── Cloud_Computing_Week12_Lab_Screenshots.zip
    ├── week-13-terraform/
    │   ├── terraform_week13_lab_files.zip
    │   └── terraform_week13_screenshots.zip
    └── week-14-cicd/
        └── week14_cicd_lab_screenshots.zip
```

For the best GitHub portfolio presentation, unzip the source code archives into their folders so GitHub can preview the code files directly. The screenshot archives can stay zipped, or they can be extracted into `screenshots/` folders if visual evidence is important.

## Notes for Running the Code

Many of these files are designed to run in a Google Cloud project and may create billable resources. Before running any commands, update project IDs, regions, zones, bucket names, repository names, and service account names.

Recommended precautions:

- Use a dedicated Google Cloud project for testing.
- Set a budget alert before creating resources.
- Review scripts before running them.
- Delete or destroy resources after testing.
- Do not commit service account keys, credentials, `.env` files, or secrets.
- Prefer service account impersonation or short lived credentials over downloaded JSON keys.

## Portfolio Value

This repository demonstrates practical cloud engineering experience across the full lifecycle of cloud work. It includes cloud setup, infrastructure provisioning, secure networking, database integration, serverless automation, managed AI services, containerization, Kubernetes orchestration, infrastructure as code, and CI/CD deployment workflows.

It is especially useful as a portfolio repository because it shows both written technical documentation and hands on implementation artifacts.
