---
layout: "default"
title: "🛡️ Sentinel-C - Monitor Your Files Safely"
description: "🛡️ Monitor and protect your systems with Sentinel-C, an advanced host defense tool offering file integrity checks, logging, and security utilities."
---

# 🛡️ Sentinel-C - Monitor Your Files Safely

> ⚠️ **Attribution Notice**  
> This page describes Sentinel-C, originally developed by [Voltsparx](https://github.com/voltsparx/Sentinel-C).  
> This repository is a **fork for attribution and reference purposes only**.  
> Original repository: [https://github.com/voltsparx/Sentinel-C](https://github.com/voltsparx/Sentinel-C)

[![Download Sentinel-C](https://img.shields.io/badge/Download%20Sentinel--C-v1.0.0-blue.svg)](https://github.com/voltsparx/Sentinel-C/releases)

## 📜 Overview

Sentinel-C is a host-based file integrity monitor built in C and C++. It helps you keep track of changes in your files, ensuring that your important data remains secure. With features like logs and HTML reports, you can quickly see any file modifications. The colored terminal output makes tracking changes easy and straightforward.

## 🖥️ System Requirements

- **Operating System:** Windows 10, macOS Mojave or later, or any Linux distribution with a modern C/C++ compiler  
- **RAM:** At least 2 GB  
- **Disk Space:** Minimum 100 MB available  
- **Dependencies:**  
  - C/C++ compiler (GCC, Clang, or Visual Studio)  
  - Make (for building the application)

## 🚀 Getting Started

### Installation Steps

1. **Download Sentinel-C**  
   [Visit this page to download](https://github.com/voltsparx/Sentinel-C/releases) the latest release.

2. **Extract the Files**  
   Extract the archive to a location of your choice (Desktop or dedicated folder recommended).

3. **Build the Application**  
   Open a terminal in the extracted folder and run:  
   ```bash
   make
   ```

4. **Run Sentinel-C**  
   ```bash
   ./sentinel-c
   ```

5. **Start Monitoring**  
   Configure the directory to monitor. Logs and HTML reports will be generated automatically.

## 🌟 Features

- File Monitoring: Track changes in specific directories  
- Detailed Logs: Keep historical records of file modifications  
- HTML Reports: User-friendly reporting  
- Colored Terminal Output: Quickly identify changes  
- Customizable Settings: Adjust monitoring to your needs

## 📄 Usage

For basic monitoring:  
```bash
./sentinel-c -monitor /path/to/directory
```

Replace `/path/to/directory` with the folder you want to monitor.

## 🔧 Configuration

Edit the configuration file to adjust:

- Monitoring Interval  
- Log Location  
- Alert Settings

## 📊 Viewing Reports

Open the HTML report in your browser from the reports directory to see tracked changes.

## ❓ Troubleshooting

- **App Does Not Start:** Verify dependencies and current working directory  
- **Logs Not Generated:** Ensure monitored directories have files and proper permissions  
- **Empty Reports:** Check the monitoring interval

## 🤝 Contributing

This fork is **for attribution and reference only**. Contributions to the **original Sentinel-C repository** are welcome: [https://github.com/voltsparx/Sentinel-C](https://github.com/voltsparx/Sentinel-C)

## 💬 Contact

For questions, support, or permission requests, please refer to the **original repository** or reach out to Voltsparx.
