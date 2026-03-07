# CI/CD Tools

This repository contains the **Project (Option A: Python)** for the **Continuous Integration and Continuous Delivery (CI/CD)** course by **IBM**.  
The project demonstrates an end-to-end CI/CD workflow using **GitHub Actions**, **Tekton Pipelines**, and **Red Hat OpenShift**.

---

## 📌 Project Description

The goal of this project is to design and implement a complete CI/CD pipeline for a Python application.  
The pipeline automates **linting, unit testing, image building, and deployment** using industry-standard DevOps tools and cloud-native technologies.

This project was developed and tested in the **IBM Skills Network Labs (SN Labs)** environment using an **OpenShift cluster**.

---

## 🎯 Objectives Achieved

- Created a **GitHub Actions CI pipeline** for:
  - Python code linting
  - Unit testing
- Created **Tekton Tasks** for:
  - Linting
  - Unit testing
  - Building a container image
- Built an **OpenShift CI Pipeline** using Tekton
- Added a **deployment stage** to deploy the application to the OpenShift cluster
- Validated the pipeline through execution and screenshots

---

## 🛠 Tools & Technologies

- Python  
- GitHub Actions  
- Tekton Pipelines  
- Docker  
- Kubernetes  
- Red Hat OpenShift   

---

## 🔁 CI/CD Workflow Overview

1. **GitHub Actions**
   - Triggers on code push
   - Runs linting and unit tests

2. **Tekton Tasks**
   - Executes linting
   - Runs unit tests
   - Builds Docker image

3. **OpenShift Pipeline**
   - Uses Tekton tasks
   - Deploys the application to the OpenShift cluster

---

## 📎 Submission Requirements

The following files are included for submission:

- **GitHub Actions Workflow**
  - `.github/workflows/workflow.yaml`
- **Tekton Tasks**
  - `tekton/tasks.yaml`
- **Documentation**
  - `README.md`

---

## 📝 Task Responses

### Task 7 – Text Response
The GitHub Actions workflow was successfully created to automate linting and unit testing of the Python application. The workflow ensures code quality before progressing to image build and deployment stages.

### Task 10 – Text Response
The OpenShift CI pipeline integrates Tekton tasks to lint, test, build, and deploy the application. This demonstrates a complete CI/CD lifecycle using cloud-native DevOps tools.

---

## 📸 Screenshots Included

Screenshots are provided for the following tasks:
- **Task 6** – GitHub Actions workflow execution
- **Task 8** – Tekton tasks execution
- **Task 9** – OpenShift pipeline deployment

---

## ✅ Conclusion

This project demonstrates practical implementation of **CI/CD best practices** using modern DevOps tools. It showcases how automated pipelines improve software quality, reliability, and deployment efficiency in cloud-native environments.

---

## 👤 Author

**Nayan Nath**  
CI/CD Tools and Practices  
IBM
