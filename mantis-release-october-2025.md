---
title = "October 2025: New features in M&NTIS Platform"
date = "2025-11-07T14:12:00+02:00"
tags = ["m&ntis", "version"]
categories = ["blog"]
preview = "img/mantis-v2025.10/mantis-v4.png"
summary = "This new release enhance training with quizz, improve visibility on attack indicators, and introduce a brand-new attack scenario."
---


Our team keeps improving M&NTIS Platform, bringing new features that
enhance training realism, improve visibility on attack indicators, and
introduce a brand-new attack scenario. Here’s what’s new 👇


---

## ✨ Key Highlights

### 🧠 Blue Team Training: Interactive Quiz Interface

To support self-paced learning, we’ve added an interactive quiz interface within labs.
It challenges learners on their understanding of the attack they just analyzed — making training sessions more dynamic, engaging, and effective.

![M&NTIS Quizz](/img/mantis-v2025.10/mantis_quizz.png)


### 🔍 New IOC View in Labs

Each lab now includes an IOC (Indicators of Compromise) view.
It provides clear visibility into the traces left by an attack, helping users understand what can be detected during post-compromise analysis — IP addresses, files, registry keys, and more.
A key feature to compare what has been understood by the defenders with the proper IOC left by the adversary emulation engine.

![M&NTIS IOC View](/img/mantis-v2025.10/mantis_ioc.png)


### 🎭 New Attack Scenario: Certifombre

The attack catalog welcomes a new scenario: Certifombre, built on a Windows environment with a domain controller and an ADCS (PKI) components at its core


## Other release changes

### 🧩 Labs Enhancements

- Added confirmation prompt before stopping a lab
- Renamed “Attack graph” → “Attack report”
- Renamed “General information” → “Information”
- Removed the Stop button from learner (public) view
- Removed attack infrastructure nodes from learner view

### 🎯 Adversary Emulation

- Improved stealth of generated binaries with more realistic naming
- Updated internet IP ranges across several scenarios for better variability


### 🧬 User Activity

- Improved life orchestrator to:
- Continue life actions after an attack scenario ends
- Better handle virtual machine reboots

### 🌐 Platform

- Added a new /status page displaying API version information, providing better transparency and operational visibility.


---

This release brings greater depth to M&NTIS Platform: more realism in scenarios, more interactivity in labs, and richer insights into attack traces.

Our goal remains the same — delivering a training and simulation environment that is as immersive and authentic as real-world cyber defense.

👉 Get in touch with us today to learn more or schedule a demo!
