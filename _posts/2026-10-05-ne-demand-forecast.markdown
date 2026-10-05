---
title: "New England Demand Forecast"
layout: post
date: 2026-10-05 08:00
image: /assets/images/ne-demand-forecast-screenshot.png
headerImage: false
tag:
category: project
projects: true
author: vladimirkazarin
externalLink: https://ne-demand-forecast-njvzyctwntwcxquaahetkb.streamlit.app/
github: https://github.com/vladimir-kazarin/ne-demand-forecast
description: An unattended MLOps pipeline that forecasts next-day hourly electricity demand for New England
---

A live MLOps pipeline that forecasts tomorrow's hourly electricity demand for the ISO New England grid every morning and runs unattended — scheduled ingestion, retraining behind an automatic quality gate, one-click rollback, monitoring and alerting. Every forecast is scored against ISO-NE's own forecast and a naive same-hour-last-week baseline, and every model decision is visible on a public dashboard.

![New England Demand Forecast](/assets/images/ne-demand-forecast-screenshot.png)

Source code is on [GitHub](https://github.com/vladimir-kazarin/ne-demand-forecast).
