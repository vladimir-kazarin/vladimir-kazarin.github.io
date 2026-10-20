---
title: "Surf Window"
layout: post
date: 2026-10-13 08:00
image: /assets/images/airflow-surf-pipeline-screenshot.png
headerImage: false
tag:
category: project
projects: true
author: vladimirkazarin
externalLink: https://airflow-surf-pipeline.streamlit.app/
github: https://github.com/vladimir-kazarin/airflow-surf-pipeline
description: An Apache Airflow 3 data pipeline that rates surf conditions daily and serves them on a live dashboard
---

A daily Apache Airflow 3 pipeline that pulls hourly ocean-wave data for four surf breaks around the world (Cape Cod, Bali, Morocco and Hawaii), rates every hour for surfability, validates it, stores it in S3 as one partition per day, and serves it on a live Streamlit dashboard with each spot's best session in local time. It runs on a GitHub Actions schedule that authenticates to AWS with OIDC, so no AWS keys are stored, and the infrastructure is defined in Terraform.

![Surf Window](/assets/images/airflow-surf-pipeline-screenshot.png)

Source code is on [GitHub](https://github.com/vladimir-kazarin/airflow-surf-pipeline).
