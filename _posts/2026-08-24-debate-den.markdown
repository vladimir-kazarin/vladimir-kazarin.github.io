---
title: "Pip & Hazel's Debate Den"
layout: post
date: 2026-08-24 08:00
image: /assets/images/debate-den-screenshot.png
headerImage: false
tag:
category: project
projects: true
author: vladimirkazarin
externalLink: https://ai-debate-den.fly.dev
github: https://github.com/vladimir-kazarin/ai-debate-den
description: Two AI personas debate any topic you throw at them, live
---

A cozy, cottagecore-styled web app where two AI personas — Pip the Fox and Hazel the Owl — debate any topic you type in, arguing opposite sides across six live-streamed turns.

![Pip & Hazel's Debate Den](/assets/images/debate-den-screenshot.png)

Under the hood it's a Node/Express backend calling the Claude API in real time, paired with a lightweight vanilla-JS frontend (no framework) that streams each argument in as it's generated. Once the debate wraps up, you pick the winner and watch the rivalry tally build over time in your browser.

Built end-to-end — design, backend, frontend, and deployment.

Source code is on [GitHub](https://github.com/vladimir-kazarin/ai-debate-den).
